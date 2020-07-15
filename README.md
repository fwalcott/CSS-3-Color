
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title> CSS 3: Color</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <script src="script.js"></script>

<h1>New In CSS 3: Color</h1>  
<br> 

<h2>CSS 3 has introduced a new way to specify colors.</h2>
<br> 
<h3> <ol> Old Way </ol> </h3>
<li> <strong> RGB-</strong> In a range from 0-255, how much red, blue and green are used to make the color (example 90. 30. 20 or 90 red, 30 blue, and 20 green).</li>
<li> <strong> Hex Code-</strong> Takes RGB and turns it to a six-digit code proceeded by a hash (example #ea3c80).</li>
<li> <strong>Color Names-</strong> They are 147 color names recognized, but this is very limiting because they are many colors that can be made with RGB.</li>
<br> 
<p> You can use color picking tools, examples being Photoshop or GIMP. You can see the RGB values specified, and the hex values are provided.</p> 
<br> 


<h3> <ul>New Way to Specify Colors: HSL </ul> </h3>

<li> <strong>Hue-</strong> What do you think of when you say the word color. Color is represented as a color wheel with a slider. You can pick what you want. </li>

<li> <strong>Saturation- </strong> of gray in a color from 0 to 100. Zero is a shade of gray, and 100 is filled with color.</li>

<li> <strong>Light-</strong> (sometimes called luminosity) The amount of white and black in a color from 0 to 100. Zero is black, fifty percent average is, and one hundred percent is white.</li> 
</ul>
<br> 
<p> <em>Remember, older browsers do not support HSL. It is a good idea to add a new CSS rule which specifies color in hex code and should appear before HSL.</em> </p>
<br> 

<p>CSS 3 also introduced the <strong> opacity property,</strong> which allows you to <em>specify</em> the opacity of any element.</p> 
<p>Values go from 0.0 to 1.0, so .75 is 75% opacity, 1.0 is 100% and 0.1 is 10%. <em>Also not supported by older browsers.</em></p>

 </body>

</html>
