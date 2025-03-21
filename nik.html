<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Regalo para Nikol</title>
    <style>
        body {
            background-color: #fff8dc;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-align: center;
            padding-top: 50px;
            overflow-x: hidden;
            overflow-y: hidden;
        }

        h1 {
            color: #ff1493;
            font-size: 48px;
            text-shadow: 2px 2px #ffffff;
            margin-bottom: 80px;
        }

        .hearts {
            font-size: 40px;
            margin-bottom: 40px;
            animation: float 2s infinite ease-in-out;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .gift-box {
            position: relative;
            display: inline-block;
            width: 300px;
            height: 300px;
            background-color: #ff5e78;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.4);
            cursor: pointer;
            transition: all 0.5s ease;
        }

        .gift-box:before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            width: 30px;
            height: 300px;
            background: #fff;
            transform: translateX(-50%);
        }

        .gift-box:after {
            content: '';
            position: absolute;
            top: 50%;
            left: 0;
            width: 300px;
            height: 30px;
            background: #fff;
            transform: translateY(-50%);
        }

        .lid {
            position: absolute;
            width: 330px;
            height: 60px;
            background-color: #ff5e78;
            top: -60px;
            left: -15px;
            border-radius: 15px;
            transition: all 0.5s ease;
        }

        .content {
            display: none;
            margin-top: 60px;
            animation: fadeIn 1s ease forwards;
        }

        .flowers {
            width: 350px;
            height: auto;
            border-radius: 20px;
            box-shadow: 0 8px 15px rgba(0,0,0,0.3);
        }

        .message {
            font-size: 32px;
            color: #ff1493;
            margin-top: 30px;
            font-weight: bold;
            text-shadow: 2px 2px #ffffff;
        }

        .message-hearts {
            font-size: 40px;
            margin-top: 20px;
            color: #ff69b4;
            animation: float 2s infinite ease-in-out;
        }

        @keyframes fadeIn {
            0% {opacity: 0;}
            100% {opacity: 1;}
        }

        .gift-box.open .lid {
            transform: translateY(-150px);
        }

        .gift-box.open + .content {
            display: block;
        }

        /* Emojis flotando */
        .emoji {
            position: absolute;
            font-size: 40px;
            animation: fly 4s linear forwards;
            pointer-events: none;
            z-index: 999;
        }

        @keyframes fly {
            0% {
                opacity: 1;
                transform: translateY(0) scale(1);
            }
            100% {
                opacity: 0;
                transform: translateY(-500px) scale(1.5);
            }
        }

    </style>
</head>
<body>

    <h1>Haz clic en el regalo, Nikol</h1>

    <div class="hearts">🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾</div>

    <div class="gift-box" onclick="openGift()">
        <div class="lid"></div>
    </div>

    <div class="content">
        <img class="flowers" src="images.jpeg" alt="Flores amarillas">
        <div class="message">
            ¡Feliz 21 de marzo, Nikol!<br>Te quiero mushoo :3
        </div>
        <div class="message-hearts">
            🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾🫶🏾
        </div>
    </div>

    <!-- Contenedor del audio -->
    <audio id="music" src="floricienta.mp3"></audio>

    <script>
        let emojisLaunched = false;

        function openGift() {
            const giftBox = document.querySelector('.gift-box');
            const music = document.getElementById('music');

            giftBox.classList.toggle('open');

            if (giftBox.classList.contains('open')) {
                music.play();
                if (!emojisLaunched) {
                    launchEmojis();
                    emojisLaunched = true;
                }
            } else {
                music.pause();
                music.currentTime = 0;
                emojisLaunched = false;
            }
        }

        function launchEmojis() {
            const totalEmojis = 50;

            for (let i = 0; i < totalEmojis; i++) {
                const emoji = document.createElement('div');
                emoji.classList.add('emoji');
                emoji.style.left = Math.random() * window.innerWidth + 'px';
                emoji.style.top = (window.innerHeight - 100) + 'px';
                emoji.innerHTML = '🫶🏾';

                document.body.appendChild(emoji);

                // Quitar el emoji después de la animación
                setTimeout(() => {
                    emoji.remove();
                }, 4000);
            }

            // Lluvia continua (opcional)
            setTimeout(() => {
                if (emojisLaunched) launchEmojis();
            }, 2000);
        }
    </script>

</body>
</html>
