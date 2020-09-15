# Animated Charts

Charts are better for diplaying data vidually than table and they are easier to look at. They aren't that easy to make though. To start you must have Chart.js, this is a JavaScript plugin to use HTML5 elements to draw the graph on a page. You can use this to make certain charts like:
 - line charts
 - bar charts
 - pie charts

You have to add the canvas element to the HTML page to draw out the chart. Then you write a script that will retrieve the context of the canvas and you add this to the footer. Chart.js is simple to use and really very flexible.

## The canvas element

The canvas element normally has two attributes; width and height and the canvas will be initially 300 pixels wide and 150 pixels high. This element can be sized by CSS, but when the image is being rendered the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will be distorted. You always want to make sure that you hava an id attribute. The id attribute isn't specific to the canvas element but is a global HTML attribute that can be applied to any HTML element and it makes it easier to find in a script. The canvas element can be styled like any other normal image, but they don't affect the actual drawing on the canvas. It is easy to display in older browsers not supporting it by using fallback content. All you have to do is alternate content on the inside of the canvas element.

You can check for support in the script programmatically by simply testing for the presence of the getContext() method.

## Drawing shapes with canvas

You need to have a canvas grid or coordinate space before you can start drawing. to draw a rectangle you would use this syntax:
 - fillRect(x,y,width,height)
 - strokeRect(x,y,width,height)
 - clearRect(x,y,width,height)

each of these three functions takes the same parameters. x and y specify the position on the canvas of the top-left corner of the rectangle and width and height provide the size.

Drawing paths:
First create the path, then use drawing commands to draw into the path, once it was created, you can stroke or fill the path to render it and here are the functions to perform the tasks:
 - beginPath()
 - Path Methods
 - stroke()
 - fill()

A very useful tool is the moveTo() function, it doesn't really draw anything but becomes part of a path list and to create lines you can use the method; lineTo(). To create arcs you need to use the arc() or arcTo() methods.

There are many more methods to use to create drawings and shapes and you can combine any of the methods for a page.

## Colors

You can apply colors to specific shapes with these properties:
 - fillStyle = color
 - strokeStyle = color

you can make things transparent by using the globalAlpha() property. You can use these properties to style lines:
 - lineWidth = value
 - lineCap = type
 - lineJoin = type
 - miterLimit = value
 - getLIneDash() 
 - setLineDash(segments)
 - lineDashedOffset = value

You can also create patterns using the property: createPattern(image,type):
 - repeat
 - repeat-x
 - repeat-y
 - no-repeat
These need to be a sting telling the type how to use the image.

Shadows:
 - shadowOffsetX = float
 - shadowOffsetY = float
 - shadowBlur = float
 - shadowColor = color

## Drawing text

to render text there are two methods you could use
 - fillText(text,x,y [, maxWidth])
 - strokeText(text, x,y[, maxWidth])
Styling the text you would use:
 - font = value
 - textAlign = value
 - textBaseLine = value
 - direction = value

Advanced text measurements:
 - measureText()

[<==Back](README.md)