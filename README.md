<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Clickable Image to YouTube</title>
  <style>
    body {
      background-color: #f4f4f4;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }
    .clickable-img {
      width: 300px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
      cursor: pointer;
      transition: transform 0.2s ease;
    }
    .clickable-img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <h1>Click the image to watch on YouTube</h1>

  <!-- Clickable image that redirects to YouTube -->
  <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank" rel="noopener noreferrer">
    <img src="https://i.imgur.com/0Xq6Q0v.png" alt="Click Me" class="clickable-img"/>
  </a>

</body>
</html>

