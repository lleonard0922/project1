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

from htp.css //chatgpt assisted so I could get the cards to flip and glow
 transform-style: preserve-3d;
    transform: rotateY(180deg);
}

.ranking-cards:hover .card-inner{
    transform: rotateY(0deg);
    transform: scale(1.05);
    box-shadow: 0 0 30px rgba(52, 152, 219, 1), 0 0 60px rgba(52, 152, 219, 0.5);
}
.card-front{
    color:black;
}

.card-back{
    transform: rotateY(180deg);
    overflow: hidden;
    padding: 0;
    background: white;
}
