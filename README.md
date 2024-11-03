<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proposal</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0e4d7;
            font-family: Arial, sans-serif;
        }
        .container {
            text-align: center;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #ff6f61;
        }
        button {
            padding: 10px 20px;
            background-color: #ff6f61;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff3b2f;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>I Love You!</h1>
        <p>Will you be my girlfriend?</p>
        <button onclick="showMessage()">Yes</button>
    </div>
    <script>
        function showMessage() {
            alert("You made me the happiest person in the world!");
        }
    </script>
</body>
</html>
