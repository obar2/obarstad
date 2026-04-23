# obarstad

geog3540/obarstad - Barstad, Owen


Testing 123
Assignment 07 SEES3540


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Simple Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background-color: #f4f4f4;
    }

    .content {
      background: white;
      padding: 20px;
      border-radius: 10px;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    img.inline-img {
      width: 50px;
      height: 50px;
      vertical-align: middle;
      border-radius: 5px;
      margin: 0 5px;
    }

    button {
      margin-top: 15px;
      padding: 10px 15px;
      border: none;
      background-color: #007BFF;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <div class="content">
    <p id="text">
      This is a simple paragraph with an image inside 
      <img src="https://via.placeholder.com/50" alt="placeholder" class="inline-img">
      the text.
    </p>

    <button onclick="changeText()">Click Me</button>
  </div>

  <script>
    function changeText() {
      document.getElementById("text").innerHTML = 
        'You clicked the button! Here is another image ' +
        '<img src="https://via.placeholder.com/50/ff0000" class="inline-img">';
    }
  </script>

</body>
</html>