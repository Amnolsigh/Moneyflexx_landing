# Moneyflexx_landing
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Money FlexX - Sureshot Bet & Loss Recovery</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: black;
            color: white;
            text-align: center;
        }
        .container {
            padding: 50px 20px;
        }
        .logo {
            font-size: 42px;
            font-weight: bold;
            color: #FFD700; /* Gold */
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 0 0 10px #FFD700;
        }
        .headline {
            font-size: 32px;
            font-weight: bold;
            margin: 20px 0;
            color: #00FF00; /* Neon Green */
            text-shadow: 0 0 10px #00FF00;
        }
        .subheadline {
            font-size: 22px;
            font-weight: 600;
            margin-bottom: 20px;
            color: #FF4500; /* Bright Orange */
            text-shadow: 0 0 10px #FF4500;
        }
        .countdown {
            font-size: 26px;
            font-weight: bold;
            color: #FF0000; /* Red */
            text-shadow: 0 0 10px #FF0000;
            margin: 20px 0;
        }
        .join-btn {
            display: inline-block;
            background: #32CD32; /* Lime Green */
            color: black;
            font-size: 24px;
            padding: 15px 30px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
            margin: 20px;
            transition: 0.3s;
            box-shadow: 0 0 15px #32CD32;
        }
        .join-btn:hover {
            background: #FFD700;
            color: black;
            box-shadow: 0 0 20px #FFD700;
        }
        .features {
            font-size: 20px;
            line-height: 1.6;
            margin-top: 30px;
        }
        .features span {
            color: #FFD700; /* Gold */
            font-weight: bold;
            text-shadow: 0 0 10px #FFD700;
        }
        .footer {
            margin-top: 50px;
            font-size: 16px;
            opacity: 0.8;
        }
    </style>
</head>
<body>

    <div class="container">
        <p class="logo">💰 Money FlexX 💰</p>

        <a href="https://t.me/+SyWmUsaNhUc1M2Fl" class="join-btn">🔥 Join Now 🔥</a>

        <h1 class="headline">🚀 100% Sureshot Bets | Loss Recovery Guaranteed 🚀</h1>

        <h2 class="subheadline">"Win Big, Lose Small – Play Smart with Money FlexX!"</h2>

        <!-- Countdown Timer -->
        <p class="countdown">⏳ Offer Ends In: <span id="timer">1:00:00</span> ⏳</p>

        <div class="features">
            <p>✔ <span>100% Accurate Betting Tips</span> – No More Guesswork, Only Profits!</p>
            <p>✔ <span>Loss Recovery Plans</span> – Win Back Your Losses in No Time</p>
            <p>✔ <span>Lightning-Fast Withdrawals</span> – Your Money, Your Control</p>
            <p>✔ <span>VIP Signals & Exclusive Insights</span> – Only for Serious Players</p>
        </div>

        <a href="https://t.me/+SyWmUsaNhUc1M2Fl" class="join-btn">🔥 Join Now 🔥</a>

        <p class="footer">⚡ Powered by Money FlexX - The No.1 Betting Channel ⚡</p>
    </div>

    <script>
        // Countdown Timer Script
        function startCountdown(duration) {
            let timer = duration, hours, minutes, seconds;
            setInterval(function () {
                hours = Math.floor(timer / 3600);
                minutes = Math.floor((timer % 3600) / 60);
                seconds = timer % 60;

                minutes = minutes < 10 ? "0" + minutes : minutes;
                seconds = seconds < 10 ? "0" + seconds : seconds;

                document.getElementById("timer").textContent = hours + ":" + minutes + ":" + seconds;

                if (--timer < 0) {
                    timer = duration;
                }
            }, 1000);
        }

        // Start 1-hour countdown
        window.onload = function () {
            startCountdown(3600);
        };
    </script>

</body>
</html>
