<!DOCTYPE html>
<html>
<head>
    <title>Simple Click Game</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
            background-color: #f2f2f2;
        }
        button {
            font-size: 20px;
            padding: 15px 30px;
            cursor: pointer;
        }
        h1 {
            color: #333;
        }
    </style>
</head>
<body>

    <h1>Click the Button Game 🎯</h1>
    <p>Score: <span id="score">0</span></p>

    <button onclick="increaseScore()">Click Me!</button>

    <script>
        let score = 0;

        function increaseScore() {
            score++;
            document.getElementById("score").innerText = score;
        }
    </script>

</body>
</html>
