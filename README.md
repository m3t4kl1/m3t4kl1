<div style="width: 100%; overflow: hidden;">
  <div style="display: inline-block; animation: roll 2s infinite linear;">
    <div style="width: 50px; height: 50px; background-color: red;"></div>
  </div>
</div>

<style>
  @keyframes roll {
    0% { transform: translateX(0); }
    100% { transform: translateX(calc(100vw - 50px)); }
  }
</style>
