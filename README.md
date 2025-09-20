<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> replace() </h2>
    <p id="out"> </p>
    <script>
        let text="I Love Chocolates";
        let result= text.replace(/Chocolates/, "Pastries");
        document.getElementById("out").innerText=result;
    </script>
</body>
</html>
