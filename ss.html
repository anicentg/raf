<html>
<head>
    <title>Annoying Game</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        #canvasContainer {
            position: relative;
            width: fit-content;
        }
        canvas {
            display: block; /* This removes any extra space around the canvas */
        }
        #flashScreen {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: red;
            display: none;
        }
    </style>
</head>
<body>
    <div id="canvasContainer">
        <canvas id="imageCanvas" width="322" height="322"></canvas>
        <div id="flashScreen"></div>
    </div>

    <script>
        const canvas = document.getElementById('imageCanvas');
        const ctx = canvas.getContext('2d');
        const flashScreen = document.getElementById('flashScreen');
        let img = new Image();
        let violationCount = 0;

        img.crossOrigin = 'Anonymous'; // Handle CORS
        img.onload = function() {
            canvas.width = img.width;
            canvas.height = img.height;
            ctx.drawImage(img, 0, 0);
        };
        img.src = 'https://i.imgur.com/3j4UIlc.png'; // Image URL

        // Event listener for mouse hover
        canvas.addEventListener('mousemove', function(event) {
            const rect = canvas.getBoundingClientRect();
            const x = event.clientX - rect.left;
            const y = event.clientY - rect.top;
            const pixel = ctx.getImageData(x, y, 1, 1).data;

            // Check if color is black or near black
            if (pixel[0] < 30 && pixel[1] < 30 && pixel[2] < 30) {
                if (violationCount === 0) {
                    flashScreen.style.display = 'block';
                    setTimeout(function() {
                        flashScreen.style.display = 'none';
                        resetPlayerPosition();
                    }, 1000); // Flash for 1 second
                    violationCount++;
                } else if (violationCount === 1) {
                    playScreamerVideo();
                }
            }
        });

        function resetPlayerPosition() {
            // Code to reset the player's position.
            // This will depend on how player position is handled in your game.
        }

        function playScreamerVideo() {
            let video = document.createElement('video');
            video.src = 'path_to_your_screamer_video.mp4'; // Set the source to your video
            video.autoplay = true;
            document.body.appendChild(video);

            // Optional: full-screen the video for effect
            if (video.requestFullscreen) {
                video.requestFullscreen();
            }
        }
    </script>
</body>
</html>
