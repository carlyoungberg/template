<!DOCTYPE html>

<html lang="en">
    
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="keywords" content="two-day multisport event, running, biking, swimming">
    <meta name="author" content="Carl Youngberg">
    <title>Ace in the Hole | Home</title>
    <link rel="stylesheet" href="css/css.css">
    <link rel="stylesheet" href="java/js.js">
    
</head>
<body>
    <header>
        <section>
            <div><img id="logo" src="images/" alt="logo" style="width:100px; height:100px;"></div>
            <div class="comp">
                <h1>Ace in the Hole</h1>
            </div>
            <div class="topnav">
                <a class="active" href="template.html">Home</a>
                <a href="events.html">Events</a>
                <a href="registration.html">Register</a>
                <a href="contact.html">Contact</a>
            </div>
        </section>
    </header>
        <article class="tmp">
            <h3>perspiciatis</h3>
            <ul>
                <li>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto </li>
                <li>Sed ut perspiciatis </li>
                <li>Sed ut perspiciatis unde omnis iste natus error sit volupt</li>
                <li>Sed ut perspiciatis</li>
                <li>Sed ut perspiciatis</li>
            </ul>
            <h3>Sed ut perspiciatis</h3>
            <ul>
                <li>Sed ut perspiciatis</li>
                <li>Sed ut perspiciatis</li>
                <li>Sed ut perspiciatis</li>
            </ul>
        </article>
            <div class="bring">
            <h3> Sed ut perspiciatis</h3>
            <p>Sed ut perspiciatis</p><br>
            <p>Sed ut perspiciatis</p>
            </div>
            <article><img src="images/" class="reg" alt="swimmer">
            <h3>perspiciatis unde</h3>
            <p> Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto </p></article>
            <article><img src="images" class="reg" alt="biker">
            <h3>perspiciatis unde</h3>
            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto </p></article>
            <article><img src="images/" class="reg" alt="runner">
            <h3>perspiciatis unde</h3>
            <p> Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto </p>
        <div class="slide">
                <img class="mySlides" src="images/placeholder.jpeg" style="width:100%" alt="Ace in the Hole1">
                <img class="mySlides" src="images/placeholder.jpeg" style="width:100%" alt="Ace in the Hole2">
                <img class="mySlides" src="images/placeholder.jpeg" style="width:100%" alt="Ace in the Hole3">
                <img class="mySlides" src="images/placeholder.jpeg" style="width:100%" alt="Ace in the Hole4">
                <img class="mySlides" src="images/placeholder.jpeg" style="width:100%" alt="Ace in the Hole5">
                <button onclick="plusDivs(-1)">&#10094;</button>
                <button onclick="plusDivs(1)">&#10095;</button>
        </div>
        <script>
            var slideIndex = 1;
            showDivs(slideIndex);

            function plusDivs(n) {
              showDivs(slideIndex += n);
            }

            function showDivs(n) {
              var i;
              var x = document.getElementsByClassName("mySlides");
              if (n > x.length) {slideIndex = 1}    
              if (n < 1) {slideIndex = x.length}
              for (i = 0; i < x.length; i++) {
                 x[i].style.display = "none";  
              }
              x[slideIndex-1].style.display = "block";  
            }
        </script>
        </article>
            <div ><a>consequuntur magn</a><br></div>     
    <footer>
        <div><img class="logo" src="images/"></div>
        <p>Ace In The Hole</p>
            <img src="images/">
            <img src="images/">
    </footer>
</body>
</html>
