<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love for Nana</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #ffcccb;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .heart {
            position: relative;
            width: 300px;
            height: 300px;
            background: red;
            transform: rotate(-45deg);
            margin: 0 auto;
        }
        .heart::before,
        .heart::after {
            content: '';
            position: absolute;
            width: 300px;
            height: 300px;
            background: red;
            border-radius: 50%;
        }
        .heart::before {
            top: -150px;
            left: 0;
        }
        .heart::after {
            left: 150px;
            top: 0;
        }
        .message {
            position: absolute;
            z-index: 10; /* Memastikan teks di atas hati */
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%); /* Mengatur teks tetap di tengah */
            color: white;
            font-size: 20px;
            font-weight: bold;
            text-align: center;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            white-space: nowrap; /* Menghindari pemotongan teks */
        }
        .message span {
            display: block;
        }
    </style>
</head>
<body>
    <div class="heart"></div>
    <div class="message">
        <span>SELAMAT PAGI</span>
        <span>NANA CANTIKK</span>
        <span>❤️❤️❤️❤️❤️</span>
    </div>
</body>
</html>
