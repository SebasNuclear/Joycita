<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Letter for You</title>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        :root {
            --bg-color: #fdf5f5;
            --paper-color: #fffdfa;
            --text-color: #4a3b3b;
            --accent-color: #9bd8f7;
        }

        body {
            background-color: var(--bg-color);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            font-family: 'Playfair Display', serif;
        }

        .letter-container {
            width: 90%;
            max-width: 600px;
            background-color: var(--paper-color);
            padding: 50px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1), inset 0 0 100px rgba(220,180,150,0.1);
            border: 1px solid #eee;
            position: relative;
            transform: rotate(-1deg);
        }

        .letter-header {
            font-family: 'Great Vibes', cursive;
            font-size: 2.5rem;
            color: var(--accent-color);
            margin-bottom: 30px;
        }

        .letter-body {
            font-size: 1.2rem;
            line-height: 1.8;
            color: var(--text-color);
            text-align: justify;
        }

        .letter-footer {
            margin-top: 40px;
            font-family: 'Dancing Script', cursive;
            font-size: 1.8rem;
            text-align: right;
            color: var(--accent-color);
        }

        .wax-seal {
            position: absolute;
            bottom: 20px;
            left: 50px;
            width: 60px;
            height: 60px;
            background: radial-gradient(circle, rgb(129, 238, 255) 20%, rgb(127, 217, 233) 80%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
            font-size: 30px;
            color: rgba(255,255,255,0.4);
            transform: rotate(15deg);
        }

        .wax-seal::after {
            content: '❤';
            color: white;
            font-size: 24px;
        }
    </style>
</head>
<body>

    <div class="letter-container">
        <div class="letter-header">Mi amada Joycita 🤍,</div>
        
        <div class="letter-body">
            <p>Me atrevo a tomarme el tiempo para escribirte de esta manera ❤️ me inspiré en las veces que tú lo haz hecho mi amor 😍💕 y quiero demostrarte de mil formas diferentes lo mucho que te amo preciosa 💓.</p>
            
            <p>No hay instante en que no te piense 🥰 y que siempre hagas latir mi corazón como loco 💓😍 eso me encanta porque significa que eres mi mayor motivación en esta vida 🫶💗 y siempre será así mi reina ❤️👑.</p>
            
            <p>Te amo mucho mi corazón 💓 realmente quiero todo contigo y solamente contigo ❤️🫶 nuestro futuro juntos será único y maravillso 😍🫶❤️ te prometo que cada día te amaré como el primer día y todavía más ❤️💓💗😍. Mi amor ❤️ mi vida 💗 mi corazón 💓 mi cielo 🥰 mi novia 😍 mi futura esposa ❤️😍 y 😍🫶 la madre de mis hijos 💗❤️💕 te amo infinitamente🤍✨🩵🌕</p>
        </div>

        <div class="letter-footer">
            Atentamente,<br>
            El amor de tu vida, Sebastián 🩵
        </div>

        <div class="wax-seal"></div>
    </div>

</body>
</html>
