<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  color: lime;  
}
header {
 color: lime; ; 
  padding: 20px;
}
header h1 {
  margin: 0;
}
nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
nav li {
  display: inline-block;
  margin-right: 10px;
}
nav a {
  text-decoration: none;
  color: lime; ;
}
main {
  padding: 20px;
}
#products li {
  background-color: #f9f9f9;
  padding: 10px;
  margin-bottom: 10px;
}
footer {
  color: lime;
  padding: 20px;
  text-align: center;
}


body{
  background: #000;
  padding-top: 10px;
} 

p{
  color: lime; 
  font-family: "Courier";
  font-size: 16px;
  margin: 10px 0 0 10px;
  white-space: nowrap;
  overflow: hidden;
  width: 30em;
  animation: type 4s steps(60, end); 
}

p:nth-child(2){
  animation: type2 8s steps(60, end);
}

p a{
  color: lime;
  text-decoration: none;
}

span{
  animation: blink 1s infinite;
}

@keyframes type{ 
  from { width: 0; } 
} 

@keyframes type2{
  0%{width: 0;}
  50%{width: 0;}
  100%{ width: 100; } 
} 

@keyframes blink{
  to{opacity: .0;}
}

::selection{
  background: black;
}

.cube {
    width: 100px;
    height: 100px;
    position: relative;
    transform-style: preserve-3d;
    animation: roll-cube 5s linear infinite;
}

.face {
    position: absolute;
    width: 100px;
    height: 100px;
}

.one {
    transform: rotateX(90deg) translateZ(50px);
    background: lime;
}

.two {
    transform: translateZ(50px);
    background: green;
}

.three {
    transform: rotateY(90deg) translateZ(50px);
    background: green;
}

.four {
    transform: rotateY(180deg) translateZ(50px);
    background: lime;
}

.five {
    transform: rotateY(-90deg) translateZ(50px);
    background: green;
}

.six {
    transform: rotateX(-90deg) translateZ(50px);
    background: lime;
}

@keyframes roll-cube {
    from {
        transform: rotateX(0deg) rotateY(0deg);
    }
    to {
        transform: rotateX(360deg) rotateY(360deg);
    }
}
</style>


<main>
	<center><div class="cube">
    <div class="face one"></div>
    <div class="face two"></div>
    <div class="face three"></div>
    <div class="face four"></div>
    <div class="face five"></div>
    <div class="face six"></div>
</div>
</div>
<br>
<br>
	<br>
	<br>
	<br>
	<br>
<br>
	<br>
	<br>
	<p>Opening Soon...</p>
<p>
  <a href="#" title="Azik Samarkandiy">Great things are coming be paient</a> 
:)<span>|</span></p> 
      
      </ul>
    </main>
