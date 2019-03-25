<!DOCTYPE HTML>
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="css/breatheartmain_css.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Pacifico|Quicksand|Raleway" rel="stylesheet">
  </head>

    <body>
        <div id="mySidebar" class="sidebar">
          <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">close</a>
        <a href="breatheartmain.html" target="_blank">Homepage</a>
        <a href="happy.html" target="_blank">Happy moments</a>
        <a href="angry.html" target="_blank">Angry moments</a>
        <a href="relaxed.html" target="_blank">Relaxed moments</a>
        <a href="about_page.html" target="_blank">About</a>

        <br>
        <a href="https://www.facebook.com/GUSewingSoc/" target="_blank" class="facebook"><i class="fa fa-facebook"></i></a>
        <a href="https://twitter.com/?lang=en-gb" target="_blank" class="twitter"><i class="fa fa-twitter"></i></a>
        <a href="https://www.instagram.com/gusewingsoc/"target="_blank" class="instagram"><i class="fa fa-instagram"></i></a>
      </div>

      <div id="main">
        <button class="openbtn" onclick="openNav()">Menu</button>

      <div class="main">

        <div class="header">
        <h1>Breathe Art</h1>
        <h3> Take a deep breath </h3> <!--content explanation-->
      </div>
      <h3>Welcome!</h3>
      <p>
        There is nothing that touches people the way art does. Life can be so stressful but to look at something beautiful, something that someone created to be seen, to evoke a reaction, is the most relaxing thing in the world. But let's take it a step further, let's breathe and be mindful. Breathe and art. Take your time, see what you need, think about how you feel and have a look through the art and breathing exercises to feel grounded again!
      </p>
      <h3>& enjoy!</h3>

      <div class="list_main">
        <ul>
          <li>
            <a href="angry.html">
              <img src="the_scream.jpg" alt="Happy_link" style="max-width:200px;max-height:200px;border:0;">
            </a>
          </li>
          <li>
            <a href="happy.html">
              <img src="happy.jpg" alt="Happy_link" style="max-width:200px;max-height:200px;border:0;">
            </a>
          </li>
          <li>
            <a href="relaxed.html">
              <img src="relax.jpg" alt="Happy_link" style="max-width:200px;max-height:200px;border:0;">
            </a>
          </li>
        </ul>
      </div>

  </div>
 </body>

              <script>
                function openNav() { document.getElementById("mySidebar").style.width = "250px";
                  document.getElementById("main").style.marginLeft = "250px";
                }
                function closeNav() { document.getElementById("mySidebar").style.width = "0";
                  document.getElementById("main").style.marginLeft= "0";
                }
          </script>

  </html>
