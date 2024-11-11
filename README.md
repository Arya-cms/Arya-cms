
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Just for You ❤️</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFDEE9;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        h1 {
            color: #FF5E79;
            font-size: 3em;
            text-align: center;
        }
        p {
            font-size: 1.5em;
            max-width: 600px;
            text-align: center;
        }
        .heart {
            font-size: 5em;
            color: #FF5E79;
            animation: heartbeat 1.5s infinite;
        }
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        button {
            padding: 10px 20px;
            font-size: 1em;
            background-color: #FF5E79;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #FF4A6B;
        }
    </style>
</head>
<body>
    <div class="heart">❤️</div>
    <h1>Hey Beautiful!</h1>
    <p>I just wanted to say how much you mean to me. You make every day brighter and fill my life with so much happiness.</p>
    <p>I'm so grateful to have you. You are my everything. ❤️</p>
    <button onclick="alert('I love you so much!')">Click Me</button>
</body>
</html>

<!---
Arya-cms/Arya-cms is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
