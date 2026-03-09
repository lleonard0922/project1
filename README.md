# project1
repo for project

  from history.css// chatgpt assisted so I could get the flash to work 
  box-shadow: 0 0 20px rgba(0,0,0,0.4);
    animation: flashBorder 1.2s infinite;
}

@keyframes flashBorder {
    0% {
        border-color: black;
        box-shadow: 0 0 5px black;
    }
    50% {
        border-color: gold;
        box-shadow: 0 0 20px gold;
    }
    100% {
        border-color: black;
        box-shadow: 0 0 5px black;
    }
}

