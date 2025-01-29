<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Go Out With Me?</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            font-family: Arial, sans-serif;
            background: url('https://source.unsplash.com/1600x900/?love,romantic') no-repeat center center/cover;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        h1 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .buttons {
            display: flex;
            gap: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 1.2rem;
            cursor: pointer;
            border: none;
            border-radius: 10px;
            transition: 0.3s;
        }
        .yes {
            background-color: #4CAF50;
            color: white;
        }
        .no {
            background-color: #FF4136;
            color: white;
            position: relative;
        }
        .no:hover {
            position: absolute;
            left: calc(50% - 100px + (Math.random() * 200px));
            top: calc(50% - 50px + (Math.random() * 100px));
        }
    </style>
</head>
<body>
    <h1>Will you go out with me?</h1>
    <div class="buttons">
        <button class="yes" onclick="alert('Yay! I\'m so happy! ❤️')">Yes</button>
        <button class="no">No</button>
    </div>
</body>
</html>
