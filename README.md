<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Do You Love Me?</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);
            font-family: 'Arial', sans-serif;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        .container {
            text-align: center;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 1em;
        }
        button {
            font-size: 1.5em;
            margin: 0.5em;
            padding: 0.5em 1em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            background-color: #ff6f61;
            color: #fff;
            box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        #response {
            margin-top: 2em;
            font-size: 2em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Do You Love Me?</h1>
        <button onclick="showResponse('Yes')">Yes</button>
        <button onclick="showResponse('No')">No</button>
        <div id="response"></div>
    </div>
    <script>
        function showResponse(answer) {
            document.getElementById('response').innerText = "You selected: " + answer;
        }
    </script>
</body>
</html>
