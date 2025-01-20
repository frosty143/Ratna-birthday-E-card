# Ratna-birthday-E-card
BEST WISHESH AND LOTS OF LOVE &lt;3
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            background-color: #ffebcd;
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding: 50px;
            animation: fadeIn 2s;
        }
        h1 {
            color: #ff4500;
            font-size: 50px;
        }
        p {
            font-size: 20px;
            color: #333;
        }
        .balloon {
            width: 50px;
            height: 80px;
            background-color: #ff69b4;
            border-radius: 25px;
            position: relative;
            display: inline-block;
            margin: 10px;
            animation: float 3s infinite;
        }
        .balloon:after {
            content: '';
            width: 5px;
            height: 50px;
            background-color: #000;
            position: absolute;
            bottom: -50px;
            left: 50%;
            transform: translateX(-50%);
        }
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <h1>Happy Birthday, Ratna!</h1>
    <p>Wishing you, Ratna, a day filled with love, joy, and all your favorite things!</p>
    <p>May this year bring you closer to your dreams!</p>
    <div id="balloons"></div>
    <button onclick="addBalloon()">Add a Balloon!</button>
    <p>From Frosty</p>

    <script>
        function addBalloon() {
            const balloon = document.createElement('div');
            balloon.className = 'balloon';
            document.getElementById('balloons').appendChild(balloon);
        }
    </script>
</body>
</html>
```
