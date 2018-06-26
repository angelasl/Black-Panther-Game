<!--HTML always starts with this "HEAD" code-->
<!DOCTYPE html>
<!--Set the language to English-->
<html lang="en">
    <head>
   <!--META TAGS-->
   <!-- META here means data about data - so information about the code-->
    <meta charset="utf-8"><!--Characters we are using-->
    <meta http-equiv="X-UA-Compatible" content="IE=edge"><!--What is visible-->
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->

    <meta name="description" content="Black Panther Game"/>

    <!-- The Tile shows up in the tab on the browser-->
    <!-- Add a title for your game-->
    <title> Black Panther Game</title>

    <!--CSS-->
    <link rel="stylesheet" href="style.css">

    <!--Fonts-->
    <link href="https://fonts.googleapis.com/css?family=Poor+Story" rel="stylesheet">
    <!--This is a free google font-->
    <link href="https://fonts.googleapis.com/css?family=Rajdhani" rel="stylesheet">

    </head>

    <!-- The body is where the main code lives-->
    <body>

    <!-- This section has the title and directions-->
    <section class="header">
        <p class="title">Black Panther</p>
        <p class="sub-title">A Shell Game</p>
        <p class="directions">Enter Your Name to Play:</p>
        <div class="name-input">
          <input id="name" class="player-name" name="user-name" type="text" placeholder="What's your name?">
          <br>
          <br>
          <!-- This button will say hello to the player-->
          <!--What should the button say?-->
          <button id="name-button" type="button">Submit</button>
      </div>
      <!--Add a class to the the p tag called directions. Type out the directions of the game. Use the <br> to break the line-->
      <p class="directions">Click one of the cards. If you get Shuri, you will get 5 points. If not, the computer will get 5 points. The first to 15 points will win! Make sure to click "Try Again!" between each guess.</p>
    </section>
      <!-- End of header section-->

    <!-- This section shows the images of the cards-->
    <section class="cards">
      <img id="card1" class="face-card" src="bplogo.png" alt="black panther logo">
      <img id="card2" class="face-card" src="bplogo.png" alt="black panther logo">
      <img id="card3" class="face-card" src="bplogo.png" alt="black panther logo">
      <img id="card4" class="face-card" src="bplogo.png" alt="black panther logo">
    </section>
    <!-- End of the cards section-->

    <!-- This section is where we keep track of the score-->
    <section class="score">
      <div class="message">
        <p id="text"></p>
        <!--This button will reset the card images-->
        <button id="tryagain-button" type="button">Try Again!</button>
      </div>
    </section>
    <!-- End of the score section -->

    <!-- This section is for the copyright information-->
    <section id="footer">
      <br>
      <img class="logo" src="gwclogo.png" alt="GWC logo">
      <p class="copyright">Made with <strong>vibranium</strong> by Angela Lee &copy;  2018</p>
    </section>
    <!-- End of the copyright section-->

    <!-- Link to the jQuery and JavaScript files-->
    <script src="jquery.js"></script>
    <script src="main.js"></script>
    </body>
  <!-- end of Body-->
</html>
<!-- end of document-->

