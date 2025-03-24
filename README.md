<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Startup Time Test</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <h1>Startup Time Test</h1>
    <p id="timestamp"></p>
    <script>
        document.getElementById('timestamp').innerText = 'Page loaded at: ' + new Date().toLocaleTimeString();
        console.log('Performance Timing:', window.performance.timing);
    </script>
</body>
</html>
