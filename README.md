<!-- There are 2 parts the Css and The Html part, Its easyer to see on my gist which you can see here https://gist.github.com/DogTags2/e731ba4dc2b4066ff7ba315af5ce2047 -->
<!--Html-->
<!DOCTYPE html>
<html>
  <head>
    <title>Dasmoto's Arts & Crafts</title>
  </head>
  
  <body>
    <!--Header! (Tittle) -->
    <br />
    <div class="header-image">
    <header  style="background-image:url(https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/pattern.jpeg);">
      <center>Dasmoto's Arts & Crafts</center></header>
    </div>
    <!--Brushes! -->
    <br />
    <div class="brushes">
      <header>Brushes</header>
    </div>
    <br />
    <img src="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/hacksaw.jpeg"/>
    <p class="hacksawbrushes"><strong>Hacksaw Brushes</strong>
      <br />
      Made of the highest quality oak, Hacksaw brushes are known for their weight and ability to hold paint in large amounts. Available in different sizes.
      <span class="brush-price"> Starting at $3.00 / brush.</span></p>
    <!-- Frames -->
    <br />
    <div class="frames"> 
      <header>Frames </header>
    </div> 
    <br />
    <img src="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/frames.jpeg"/>
    <p class="artframes"> <strong>Art Frames (assorted) </strong> 
      <br /> Assorted frames made of different material, including MDF, birchwood, and PDE. Select frames can be sanded and painted according to your needs. <span class="frame-price">Starting at $2.00 / frame. </span></p>
    <!--Paint! -->
    <br />
    <div class="paint"><header>Paint</header> 
    </div>
    <br />
    <img src="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/finnish.jpeg"/>
    <p class="cleanfinishpaint"> <strong>Clean Finnish Paint </strong><br />Imported paint from Finland. Over 256 colors available in-store, varying in quantity (1 oz. to 8 oz.). Clean Finnish paint microbinds to canvas, increasing the finish and longevity of any artwork. <span class="paint-price">Starting at $5.00 / tube. </span></p>
  </body>
</html>



<!--CSS-->

<p> CSS HAS BEEN GOOFED UP ON GITHUB</p>


/*Extra Background image (personaly added)*/ 
body {
  background-image:url(https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/selga.png);
}
/*Header! (title) */
.header-image {
 background-position:center;
font-size:100px;
font-family:Helvetica;
font-weight:bold;
color:khaki;
}
/*Brushes! */
.brushes {
  background-color:mediumspringgreen;
  color:white;
  font-size:32px;
  font-weight:bold;
  font-family:Helvetica;
}
.hacksawbrushes {
  font-family:Helvetica;
}
.brush-price {
  font-weight:bold;
  color:blue;
}
/*Frames! */
.frames {
  background-color:lightcoral;
  color:white;
  font-family:Helvetica;
  font-size:32px;
  font-weight:bold;
}
.artframes {
  font-family:Helvetica;
}
.frame-price {
   font-weight:bold;
  color:blue;
}
/*Paint! */
.paint {
  background-color:skyblue;
  color:white;
  font-family:Helvetica;
  font-size:32px;
  font-weight:bold;
}
.cleanfinishpaint {
 font-family:Helvetica; 
}
.paint-price {
  font-weight:bold;
  color:blue;
}
