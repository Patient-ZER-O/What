
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Click the Image</title>
  <style>
    body {
      margin: 0;
      background: #111;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    img {
      width: 400px;
      max-width: 90%;
      border-radius: 12px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4);
      cursor: pointer;
      transition: transform 0.3s ease;
    }
    img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank">
    <img src="https://i.imgur.com/0Xq6Q0v.png" alt="Click me" />
  </a>

</body>
</html>