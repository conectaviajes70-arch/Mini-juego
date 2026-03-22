<!DOCTYPE html>
<html>
<head>
  <title>Conecta Game 🐍</title>
  <style>
    body {
      background: black;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      color: white;
      font-family: Arial;
    }
    canvas {
      border: 2px solid #00f0ff;
    }
  </style>
</head>
<body>

<canvas id="game" width="300" height="300"></canvas>

<script>
const canvas = document.getElementById("game");
const ctx = canvas.getContext("2d");

let box = 15;
let snake = [{x: 150, y: 150}];
let direction = "RIGHT";
let food = {
  x: Math.floor(Math.random()*20)*box,
  y: Math.floor(Math.random()*20)*box
};

document.addEventListener("keydown", (e) => {
  if (e.key === "ArrowUp" && direction !== "DOWN") direction = "UP";
  if (e.key === "ArrowDown" && direction !== "UP") direction = "DOWN";
  if (e.key === "ArrowLeft" && direction !== "RIGHT") direction = "LEFT";
  if (e.key === "ArrowRight" && direction !== "LEFT") direction = "RIGHT";
});

function draw() {
  ctx.fillStyle = "black";
  ctx.fillRect(0, 0, 300, 300);

  for (let i = 0; i < snake.length; i++) {
    ctx.fillStyle = i === 0 ? "#00f0ff" : "#0099aa";
    ctx.fillRect(snake[i].x, snake[i].y, box, box);
  }

  ctx.fillStyle = "red";
  ctx.fillRect(food.x, food.y, box, box);

  let head = {x: snake[0].x, y: snake[0].y};

  if (direction === "UP") head.y -= box;
  if (direction === "DOWN") head.y += box;
  if (direction === "LEFT") head.x -= box;
  if (direction === "RIGHT") head.x += box;

  if (head.x === food.x && head.y === food.y) {
    food = {
      x: Math.floor(Math.random()*20)*box,
      y: Math.floor(Math.random()*20)*box
    };
  } else {
    snake.pop();
  }

  snake.unshift(head);

  // colisión
  if (
    head.x < 0 || head.y < 0 || head.x >= 300 || head.y >= 300 ||
    snake.slice(1).some(s => s.x === head.x && s.y === head.y)
  ) {
    snake = [{x:150, y:150}];
    direction = "RIGHT";
  }
}

setInterval(draw, 100);
</script>

</body>
</html>
