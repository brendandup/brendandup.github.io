<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>test</title>
    </head>
    <body>
        <p><button onclick="changePoints(1)">+1</button></p>
        <script>
            var points = 0;
            function changePoints(n) {
                points += n;
                console.log(points);
            };
        </script>
    </body>
</html>
