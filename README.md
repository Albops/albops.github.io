<html>
<head>
  <title>Botonera de sonidos</title>
  <style>
    /* CSS styles for buttons */
    .numbered-button {
      font-size: 24px; /* set the font size */
      width: 100px; /* set the width */
      height: 60px; /* set the height */
      margin: 5px; /* add margin between buttons */
      color: #fff; /* set the text color */
      border: none; /* remove button borders */
      border-radius: 5px; /* add border radius for rounded edges */
    }

    /* Custom background colors for each button */
    #button1 {
      background-color: #3498db; /* set the background color */
    }

    #button2 {
      background-color: #2ecc71; /* set the background color */
    }

    #button3 {
      background-color: #e74c3c; /* set the background color */
    }

    #button4 {
      background-color: #9b59b6; /* set the background color */
    }

    #button5 {
      background-color: #f39c12; /* set the background color */
    }

    #button6 {
      background-color: #1abc9c; /* set the background color */
    }
  </style>
  <script>
    // JavaScript code to play sounds when buttons are clicked
    function playSound(soundFile) {
      var audio = new Audio(soundFile);
      audio.play();
    }
  </script>
</head>
<body>
  <h1>Botonera de sonidos</h1>
  <button id="button1" class="numbered-button" onclick="playSound('Metal Crash.mp3')">1</button>
  <button id="button2" class="numbered-button" onclick="playSound('Plastic Object Dropping.mp3')">2</button>
  <button id="button3" class="numbered-button" onclick="playSound('Tearing Crunch.mp3')">3</button>
  <button id="button4" class="numbered-button" onclick="playSound('Water Splash on Cement Series.mp3')">4</button>
  <button id="button5" class="numbered-button" onclick="playSound('Wineglass On Wood Soft.mp3')">5</button>
  <button id="button6" class="numbered-button" onclick="playSound('Woodpecker Pecking on Tree.mp3')">6</button>
</body>
</html>
