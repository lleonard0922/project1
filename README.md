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

from styles.css// chatgpt assisted in building the casino table and allowing me to put the cards on there:
.casino-table {
        background-color: #006400; 
        border: 10px solid #8b4513; 
        border-radius: 50% / 30%;
        width: 600px;
        height: 300px;
        position: relative;
        box-shadow: 0 0 30px rgba(0,0,0,0.6);
        margin: 40px auto 20px auto;
    }

.card-container{
    position: relative;
    width: 220px;
    height: 220px;
    margin: 20px auto 40px auto;
}

.card{
    position: absolute;
    background-color: whitesmoke;
   border: 1px solid black;         
   width: 100px;
   height: 160px;
   line-height: 160px;
   text-align: center;
   font-size: 80px;
   border-radius: 5px;
   box-shadow: 3px 3px 0px black;
   color:black;
}
