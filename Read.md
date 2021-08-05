#  HTML Images; CSS Color & Text: 

## HTML Images Syntax:
![Html](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8qAGxPRhlzh_fZjd42Der0hnnxqaj4aI4Wg&usqp=CAU)

The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
## The src Attribute:
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. 
Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon.
The broken link icon and the alt text are shown if the browser cannot find the image.
## The alt Attribute:
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

Example
<img src="img_chania.jpg" alt="Flowers in Chania">

# Css color and text :
![Css](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMLcIssIpX5W_br4NzYFCSvZZOvfCATfA6Pg&usqp=CAU)
## Css Text :
The color property is used to set the color of the text. The color is specified by:

a color name - like "red"
a HEX value - like "#ff0000"
an RGB value - like "rgb(255,0,0)"
Look at CSS Color Values for a complete list of possible color values.

## css color:
The default text color for a page is defined in the body selector

Text Color and Background Color
In this example, we define both the background-color property and the color property:

Example
body {
  background-color: lightgrey;
  color: blue;
}

h1 {
  background-color: black;
  color: white;
}
