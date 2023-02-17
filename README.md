#include <stdio.h>
#include <stdlib.h>
#include <unistd.h>

void clear_screen() {
    printf("\033[2J\033[H");
}

int main(void) {
    int i, j;
    const int width = 40;
    const int height = 20;
    int cube_x = 0;
    int cube_y = 0;
    int cube_dir_x = 1;
    int cube_dir_y = 1;

    while (1) {
        clear_screen();
        for (i = 0; i < height; i++) {
            for (j = 0; j < width; j++) {
                if (i == cube_y && j == cube_x) {
                    printf("[]");
                } else {
                    printf("  ");
                }
            }
            printf("\n");
        }
        usleep(100000);
        cube_x += cube_dir_x;
        cube_y += cube_dir_y;
        if (cube_x == width - 2) {
            cube_dir_x = -1;
        } else if (cube_x == 0) {
            cube_dir_x = 1;
        }
        if (cube_y == height - 1) {
            cube_dir_y = -1;
        } else if (cube_y == 0) {
            cube_dir_y = 1;
        }
    }

    return 0;
}
