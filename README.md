<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viking do Aviator</title>
    <style>
        /* Reset básico */
        * { margin: 0; padding: 0; box-sizing: border-box; }

        body, html {
            height: 100%;
            font-family: 'Arial', sans-serif;
        }

        /* Fundo com imagem */
        body {
            background: url('https://images.unsplash.com/photo-1604079624512-4c06c9d08f2d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NzM4OTV8MHwxfHNlYXJjaHwxfHx2a2luZyUyMGF2aWF0b3J8ZW58MHx8fHwxNjkwNzQwODU2&ixlib=rb-4.0.3&q=80&w=1080') no-repeat center center fixed;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }

        /* Overlay escuro */
        .overlay {
            position: absolute;
            top: 0; left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.6);
            z-index: 1;
        }

        /* Conteúdo central */
        .content {
            position: relative;
            z-index: 2;
            max-width: 600px;
            padding: 20px;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 20px;
            text-shadow: 2px 2px 10px #000;
        }

        .btn-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 15px 30px;
            font-size: 1.2em;
            font-weight: bold;
            text-decoration: none;
            color: #fff;
            background-color: #ff6b00;
            border-radius: 10px;
            transition: all 0.3s ease;
        }

        .btn:hover {
            background-color: #ffa500;
            transform: scale(1.05);
        }

        @media(max-width: 600px) {
            h1 { font-size: 2.2em; }
            .btn { font-size: 1em; padding: 12px 25px; }
        }
    </style>
</head>
<body>
    <div class="overlay"></div>
    <div class="content">
        <h1>Viking do Aviator</h1>
        <div class="btn-container">
            <a class="btn" href="https://wa.me/5587999541301" target="_blank">WhatsApp</a>
            <a class="btn" href="https://t.me/VikingAviator" target="_blank">Telegram</a>
        </div>
    </div>
</body>
</html>
#
