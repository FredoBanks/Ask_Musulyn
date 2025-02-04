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
            background-color: #660033;
            padding: 50px;
        }
        h1 {
            color: #660033;
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
      <img src="musu.jpg" alt="Musu's Picture">
    <h1>Hi Musu, My Gorgeous Woman, Will You Be My Valentines? ❤️</h1>
     <button class="yes" onclick="yesAnswer()">Yes</button>
    <button class="no" onclick="noAnswer()">No</button>

    <script>
        function yesAnswer() {
            alert("Yayy, I love you so much twinbae! 💖");
        }

        function noAnswer() {
            alert("Wow, what a heartbreak. 😢");
        }
    </script>
</body>
</html>
