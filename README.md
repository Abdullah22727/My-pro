<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أول موقع لي</title>
    <style>
        body {
            background-color: #f4f4f4;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: #333;
        }
    </style>
</head>
<body>
    <h1>مرحبًا بك في أول موقع لي!</h1>
    <button onclick="changeColor()">اضغط لتغيير لون الخلفية</button>
    <p>هذا أول موقع أبرمجه بنفسي مش بنفسي أوي يعني بس مقدرش أنكر على نفسي مجهودي😂</p>
</body<script>
    function changeColor() {
        let colors = ["#1abc9c", "#e74c3c", "#3498db", "#9b59b6", "#f1c40f"];
        let randomColor = colors[Math.floor(Math.random() * colors.length)];
        document.body.style.backgroundColor = randomColor;
    }
</script>
