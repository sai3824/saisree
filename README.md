# saisree
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Button</title>
    <style>
     body {
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
}
     h1 {
    color: #333;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

button:focus {
    outline: none;
}

    </style>
</head>
<body>
    <h1>Interactive Button Example</h1>
    <button id="colorButton">Click me!</button>

    <script src="scripts.js"></script>
</body>
</html>

 

