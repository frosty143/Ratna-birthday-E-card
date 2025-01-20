# Ratna-birthday-E-card
BEST WISHESH AND LOTS OF LOVE &lt;3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Ratna!</title>
    <style>
        body {
            background-color: #000; /* Black background */
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        /* Outer box with border */
        .card-box {
            border: 5px dashed #ff6b81; /* Pink dashed border */
            border-radius: 20px;
            padding: 20px;
            background: linear-gradient(145deg, #333, #111); /* Subtle gradient */
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.8);
            max-width: 600px;
            width: 90%;
            text-align: center;
            animation: pop-in 1s ease-out;
        }

        /* Inner card */
        .card {
            background: #000; /* Black card background */
            border: 2px solid #ff6b81; /* Pink border */
            border-radius: 15px;
            padding: 30px 20px;
            color: #fff;
            box-shadow: 0 5px 15px rgba(255, 107, 129, 0.5);
            position: relative;
        }

        h1 {
            font-size: 3rem;
            font-weight: bold;
            color: #ff6b81;
            margin-bottom: 10px;
            text-shadow: 3px 3px 10px rgba(255, 107, 129, 0.8);
        }

        p {
            font-size: 1.2rem;
            line-height: 1.8;
            color: #e3f2fd; /* Light blue */
        }

        .highlight {
            color: #f9a825; /* Golden yellow */
            font-weight: bold;
        }

        /* Cake image */
        .cake {
            width: 200px;
            height: auto;
            margin: 20px 0;
            animation: bounce 2s infinite;
        }

        /* Floating balloons animation */
        .balloons {
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .balloons img {
            position: absolute;
            animation: float 4s infinite ease-in-out;
            opacity: 0.8;
        }

        .balloon1 {
            top: 100%;
            left: 10%;
            animation-delay: 0s;
        }

        .balloon2 {
            top: 100%;
            left: 50%;
            animation-delay: 1s;
        }

        .balloon3 {
            top: 100%;
            left: 80%;
            animation-delay: 2s;
        }

        /* Animations */
        @keyframes float {
            0% {
                transform: translateY(0) scale(1);
            }
            50% {
                transform: translateY(-50px) scale(1.05);
            }
            100% {
                transform: translateY(-100vh) scale(0.9);
            }
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }

        @keyframes pop-in {
            0% {
                transform: scale(0.5);
                opacity: 0;
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }

        footer {
            margin-top: 20px;
            font-size: 1.2rem;
            color: #ff6b81;
            text-shadow: 2px 2px 5px rgba(255, 255, 255, 0.3);
        }
    </style>
</head>
<body>
    <!-- Outer Box -->
    <div class="card-box">
        <!-- Balloons in the background -->
        <div class="balloons">
            <img src="https://i.imgur.com/Z4Ry4Ve.png" alt="Balloon 1" class="balloon1" width="100">
            <img src="https://i.imgur.com/Z4Ry4Ve.png" alt="Balloon 2" class="balloon2" width="120">
            <img src="https://i.imgur.com/Z4Ry4Ve.png" alt="Balloon 3" class="balloon3" width="90">
        </div>

        <!-- Birthday Card -->
        <div class="card">
            <h1>Happy Birthday Ratna!</h1>
            <img src="https://i.imgur.com/ZrIptAA.png" alt="Birthday Cake" class="cake">
            <p>
                Dear Ratna, on your <span class="highlight">22nd birthday</span>, I just want you to know how much you mean to me. 
                You’re the <span class="highlight">coder</span> who fills my life with endless joy, the <span class="highlight">algorithm</span> that keeps my heart running, 
                and the bug-fixer of all my worries. May your dreams compile flawlessly and your happiness never encounter an error. ❤️
            </p>
            <footer>With love, Frosty 💖</footer>
        </div>
    </div>
</body>
</html>


