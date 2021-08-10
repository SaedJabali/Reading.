# The < canvas > element

### Canvas usage
The HTML < canvas> element is used to draw graphics on a web page.
The < canvas> element is only a container for graphics. You must use JavaScript to actually draw the graphics.

Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

A canvas is a rectangular area on an HTML page. By default, a canvas has no border and no content.

**Syntax**

< canvas id="tutorial" width="150" height="150">

< /canvas>

## Draw on the Canvas With JavaScript

1. Find the Canvas Element

First of all, you must find the < canvas> element.

This is done by using the HTML DOM method getElementById():

var canvas = document.getElementById("tutorial");

2. Create a Drawing Object

Secondly, you need a drawing object for the canvas.

The getContext() is a built-in HTML object, with properties and methods for drawing:

var ctx = canvas.getContext("2d");

3. Draw on the Canvas
Finally, you can draw on the canvas.

Set the fill style of the drawing object to the color red:

ctx.fillStyle = "#FF0000";

The fillStyle property can be a CSS color, a gradient, or a pattern. The default fillStyle is black.

The fillRect(x,y,width,height) method draws a rectangle, filled with the fill style, on the canvas:

ctx.fillRect(0, 0, 150, 75);

### Canvas Coordinates
The HTML canvas is a two-dimensional grid.

The upper-left corner of the canvas has the coordinates (0,0).

ctx.fillRect(0, 0, 150, 75) means: Start at the upper-left corner (0,0) and draw a 150x75 pixels rectangle.

# Cheatsheet

![Cheatsheet](https://mk0wittysparksm75pi6.kinstacdn.com/wp-content/uploads/2017/07/HTML-Canvas-Cheatsheet.png.webp)