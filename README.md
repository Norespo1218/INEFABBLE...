<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>The Quiz's</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"><link rel="stylesheet" href="./style.css">

</head>
<body>
<body onload="displayQuote(); setTimeout(myFunction, 20000);">
<center>  
  <img src="https://www.logolynx.com/images/logolynx/fc/fc7e54569ba9b77284102311c35902ea.png" width="100%" >
  <table>  
    <tr>  
 <a href="quiz1.html" style="text-decoration:none"> <div id="big" class="big">
   PLAY QUIZ 1
</div></a>
    </tr>
    <tr>  
   <a href="Edison Quiz START.html" style="text-decoration:none">  <div id="big2" class="big">
   PLAY QUIZ 2
	   </div></a>
    </tr>
    <tr>  
       <a href="welcomeabout.html" style="text-decoration:none">  <div id="big3" class="big">
  PLAY QUIZ 3
      </div></a>
		   </tr>
    <br><br>
    <tr>
        <a id="about" class="small" href="aboutus.html" target="_blank">
        About Us
        </a>
      <a style="opacity:0" >2</a>
        <a id="grade" class="small" href="https://youtube.com/c/acemonkeyilium" target="_blank">
        Grade Us!
        </a>
    </tr>
	
  </table>  
	 <button id="play-button">CLICK THIS FIRST!</button>
 <div class="subtitle" id="quote">My name is Carl but call me anytime!</div>
</center>

 <script  src="./script.js"></script>
    <script>
	
      function playSound() {
        var audio = new Audio('George Michael - Careless Whisper (Official Video).mp3');
        audio.play();

      
        var button = document.getElementById('play-button');
        button.parentNode.removeChild(button);
      }

      document.getElementById('play-button').onclick = playSound;
		
    </script>

</body>
</html>
