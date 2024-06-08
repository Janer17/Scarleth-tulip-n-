# Scarleth-tulip-n-  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dinosaurio y Tulipán</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #ffffff;
        }
        #dinosaur {
            position: relative;
        }
        #tulip {
            position: absolute;
            left: 100px;
            top: 50px;
            transition: transform 2s;
        }
        #message {
            position: absolute;
            top: -50px;
            left: 200px;
            font-size: 24px;
            color: #000000;
        }
    </style>
</head>
<body>
    <div id="dinosaur">
        <img src="dinosaur.png" alt="Dinosaurio" id="dinoImg" width="200">
        <img src="tulip.png" alt="Tulipán" id="tulip" width="50">
        <div id="message">Eres preciosa my love</div>
    </div>

    <script>
        window.onload = function() {
            const tulip = document.getElementById('tulip');
            tulip.style.transform = 'translateY(-50px)';
        };
    </script>
</body>
</html>
