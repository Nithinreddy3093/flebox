<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello!</title>
    <style>
        #grid {
            background-color: green;
            display: grid;
            padding: 20px;
            grid-column-gap: 20px;
            grid-row-gap: 10px;
            grid-template-columns: 200px 200px auto;
        }

        .grid-item {
            background-color: white;
            font-size: 20px;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div id="grid">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>
        <div class="grid-item">4</div>
        <div class="grid-item">5</div>
        <div class="grid-item">6</div>
        <div class="grid-item">7</div>
        <div class="grid-item">8</div>
        <div class="grid-item">9</div>
        <div class="grid-item">10</div>
        <div class="grid-item">11</div>
    </div>
</body>
</html>
