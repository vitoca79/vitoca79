<html>
<head>
  <title>José cabeça deformada</title>
  <style>
    body {
      background-color: #E6F1F6;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .container {
      text-align: center;
    }

    h1 {
      color: #214F6D;
      font-family: Arial, sans-serif;
    }

    .button {
      display: inline-block;
      padding: 12px 24px;
      background-color: #4285F4;
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 16px;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .button:hover {
      background-color: #3367D6;
    }

    #videoContainer {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>clique no botão do meme</h1>
    <button class="button" onclick="playVideo()">Clique para reproduzir o meme</button>
    <div id="videoContainer"></div>
  </div>

  <script>
    function playVideo() {
      var videoContainer = document.getElementById("videoContainer");
      videoContainer.innerHTML = '<iframe width="560" height="315" src="https://www.youtube.com/embed/iC1vT9dghRM?autoplay=1" frameborder="0" allowfullscreen></iframe>';
    }
  </script>
</body>
</html>
