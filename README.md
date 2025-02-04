<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Girlfriend?</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffebf0;
            padding: 50px;
        }
        h1 {
            color: #ff4d6d;
        }
        button {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 10px;
        }
        .yes {
            background-color: #28a745;
            color: white;
        }
        .no {
            background-color: #dc3545;
            color: white;
            position: absolute;
        }
    </style>
</head>
<body>
    <h1>Hi Musu, Will You Be My Valentines? ❤️</h1>
    <button class="yes" onclick="yesAnswer()">Yes</button>
    <button class="no" id="noButton" onmouseover="moveNo()">No</button>

    <script>
        function yesAnswer() {
            alert("Yay! I Love you Twinbae! 💖");
        }

        function moveNo() {
            let button = document.getElementById("noButton");
            let x = Math.random() * (window.innerWidth - button.clientWidth);
            let y = Math.random() * (window.innerHeight - button.clientHeight);
            button.style.left = x + "px";
            button.style.top = y + "px";
        }
    </script>
</body>
</html>
