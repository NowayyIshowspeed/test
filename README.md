<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>No saying helllo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: #333;
        }

        .container {
            text-align: center;
            background: #fff;
            padding: 20px 40px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .container h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-decoration: line-through;
            color: red;
        }

        .container h2 {
            font-size: 1.2em;
            font-weight: normal;
            margin: 10px 0;
            color: #555;
        }

        .container p {
            font-size: 1em;
            color: #666;
            margin-top: 20px;
        }

        .languages {
            margin-top: 20px;
            font-size: 1.2em;
            color: #333;
        }

        .languages span {
            display: inline-block;
            margin: 5px 10px;
            font-weight: bold;
        }

        .emoji {
            font-size: 2em;
            margin-top: 10px;
        }

        @keyframes scroll {
            0% { transform: translateY(0); }
            100% { transform: translateY(-100%); }
        }

        .scrolling {
            height: 3em;
            overflow: hidden;
            position: relative;
        }

        .scrolling .languages {
            display: inline-block;
            animation: scroll 10s linear infinite;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>No Hello</h1>
        <h2>Please don't just say "hello"</h2>
        <p>Imagine calling someone on the phone, going "hello!" and then putting them on hold...</p>
        <div class="scrolling">
            <div class="languages">
                <span>Hello (English)</span>
                <span>Bonjour (French)</span>
                <span>Hola (Spanish)</span>
                <span>Hallo (German)</span>
                <span>Ciao (Italian)</span>
                <span>こんにちは (Konnichiwa - Japanese)</span>
                <span>안녕하세요 (Annyeonghaseyo - Korean)</span>
                <span>你好 (Nǐ hǎo - Chinese)</span>
                <span>Привет (Privet - Russian)</span>
                <span>Olá (Portuguese)</span>
                <span>नमस्ते (Namaste - Hindi)</span>
                <span>Hei (Norwegian)</span>
                <span>Salam (Arabic)</span>
                <span>Shalom (Hebrew)</span>
                <span>Yassas (Greek)</span>
            </div>
        </div>
        <div class="emoji">🤦‍♀️</div>
    </div>
</body>
</html>
