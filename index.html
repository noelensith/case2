<!DOCTYPE html>

<head>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #222;
        }

        canvas {
            background: #334155;
            border: 4px solid #1e293b;
            border-radius: 8px;
        }
    </style>
</head>

<body>
    <canvas id="marchCanvas" width="400" height="400"></canvas>
    <script>
        const canvas = document.getElementById('marchCanvas');
        const ctx = canvas.getContext('2d');

        //Load sprite
        const soldierSprite = new Image();
        soldierSprite.src = "Run.png";

        //Samurai sprite sheet information
        const frameWidth = 128;
        const frameHeight = 128;
        const totalFrames = 8;
        let currentFrame = 0;

        //Samurai start left side
        let posX = -frameWidth;

        //Vertical position
        const posY = 180;
        let gameFrameCount = 0;

        //Larger number = slower running animation
        const animationSpeed = 6;

        function animate() {
            //clear previous fram
            ctx.clearRect(0, 0, canvas.width, canvas.height);

            //ground line
            ctx.strokeStyle = '#475569'
            ctx.lineWidth = 2;

            ctx.beginPath();
            ctx.moveTo(0, posY + frameHeight);
            ctx.lineTo(canvas.width, posY + frameHeight);
            ctx.stroke();

            //draw curren Samurai fram
            ctx.drawImage(
                soldierSprite,
                currentFrame * frameWidth,
                0,
                frameWidth,
                frameHeight,
                posX,
                posY,
                frameWidth,
                frameHeight
            );

            //Move Samurai right
            posX += 1.5;

            //restart on left side
            if (posX > canvas.width) {
                posX = -frameWidth;
            }

            //Control animation frames
            gameFrameCount++;

            if (gameFrameCount % animationSpeed === 0) {
                currentFrame = (currentFrame + 1) % totalFrames;
            }

            requestAnimationFrame(animate);

        }

        soldierSprite.onload = () => {
            animate();
        };
    </script>
</body>
