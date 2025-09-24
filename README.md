<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> regex exe()</h2>
    <p id="out"></p>
    <script>
        let pattern= /script/i;
        let text="I learnt JavaScript";
        let result=pattern.exec(text);
        document.getElementById("out").innerText=result[3];
    </script>
</body>
</html>
