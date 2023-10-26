# conmutados

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            text-align: center;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            font-size: 18px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.2s;
        }

        .button:hover {
            background-color: #3498db;
        }

        .button:active {
            transform: translateY(2px);
        }

        #btn10 {
            background-color: #e74c3c;
        }

        #btn25 {
            background-color: #f1c40f;
        }

        #btn50 {
            background-color: #2ecc71;
        }

        #btn75 {
            background-color: #27ae60;
        }

        #btn100 {
            background-color: #FF0000;
        }

        #btnApagar {
            background-color: #34495e;
        }
    </style>
</head>
<body>
<h3>Motor</h3>
    <button class="button" id="btn10" onclick="window.location.href='#10'">10%</button>
    <button class="button" id="btn25" onclick="window.location.href='#25'">25%</button>
    <button class="button" id="btn50" onclick="window.location.href='#50'">50%</button>
    <button class="button" id="btn75" onclick="window.location.href='#75'">ApagarLed</button>
    <button class="button" id="btn100" onclick="window.location.href='#100'">Encender</button>
    <button class="button" id="btnApagar" onclick="window.location.href='#apagar'">Apagar</button>

</body>

</html>
