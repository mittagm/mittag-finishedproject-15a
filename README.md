# mittag-finishedproject-15a
* {
  margin: 0;
  padding: 0;
}

.menu {
  color: white;
  font-size: 90%;
  position:relative; 
  top: -45px;
  left: -600px;
}

#bold-text {
  padding: 10px;
}

#box {
  width: fill;
  height: 50px;
  background-color: #000000;
  border: 1px solid black;
  padding: 20px;
}


body {
  font-size: 85%;
  font-family: Arial, Helvetica, sans-serif;
  background-color: lightblue;
  line-height: 1.6;
  text-align: center;
}

#content {
  max-width: 900px;
  margin: auto;
  padding: 0 30px;
  position: relative;
  animation-name: floatingright;
  animation-duration: 3s;
  animation-fill-mode: forwards;
}

#showcase {
  height: 300px;
}

#showcase h1 {
  font-size: 50px;
  position: relative;
  line-height: 1.3;
  animation-name: floatingdown;
  animation-duration: 3s;
  animation-fill-mode: forwards;
  
}

@keyframes floatingdown {
  0% {
    top: -60px;
  }
  100% {
    top: 200px;
  }
}

@keyframes floatingright {
  0% {
    left: -1000px;
  }
  100% {
    left: 0px;
  }
}

.btn {
  display: inline-block;
  color: black;
  background-color: lightblue;
  text-decoration: none;
  border: black 1px solid;
  padding: 1rem 2rem;
  margin-top: 30px;
  margin-bottom: 50px;
  opacity: 0;
  animation-name: btn;
  animation-duration: 3s;
  animation-delay: 3s;
  animation-fill-mode: forwards;
  transition-property: transform;
  transition-duration: 2s;
}

@keyframes btn {
  0% {
   opacity: 0; 
  }
  100% {
   opacity: 1; 
  }
}

.btn:hover {
  transform: rotateY(360deg);
  background-color: deepskyblue;
  color: white;
  border-color: gray; 
}

.btn:active {
  transform: scale(1.2,1.2);
  background-color: gray
    
}
