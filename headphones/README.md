<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awesome Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f0f0f0;
        }
        a {
            color: #000; 
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover,
        a:active {
            color: #FF6565; 
        }
        button {
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            transition: opacity 0.3s ease;
        }
        button:hover,
        button:active {
            opacity: 0.9; 
        }
        @media (max-width: 480px) {
            .container {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Awesome Project</h1>
        <p>This is an example content within a container that is centered and limited to a maximum width of 1000px.</p>
        <a href="#">Example Link</a>
        <br><br>
        <button>Click Me</button>
    </div>
</body>
</html>