<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Meri Test Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Hello, World!</h1>
  <button onclick="sayHi()">Click Me</button>
  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial;
  background: #f0f0f0;
  text-align: center;
  padding: 50px;
}
button {
  padding: 10px 20px;
  border: 2px solid blue;
  background-color: white;
  color: blue;
  font-size: 18px;
  border-radius: 5px;
  transition: all 0.3s;
}
button:hover {
  background-color: blue;
  color: white;
}
function sayHi() {
  alert("Welcome to your test website!");
}
