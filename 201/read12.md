# Read12

## Chart.js API(article)
Charts are better than tables for showing data but more difficult to create. Chart.js is a plugin for creating all types of charts and to use it we must download it and copy the chart.min.js into our directory and then do the work in html.
to make a **line chart**, a **pie chart** , and a **bar chart** we use canvas element in html and a script that uses canvas element information to make the chart inside it.

## Canvas API.
### Basic usage:
Canvas element mainly has width and height attribtes and if they are not specified they are set by default to 300px width and 150px height, and we can add id attribute whenever we want exactly like other elements, and we can style it using border, background and margin, but if no styling is applied it will be transparent.
we can use fallback content inside canvas element for the old browsers which doesn't support it, and they will be omitted if the browser support canvas.

## Drawing shapes with canvas
we can draw different shapes using canvas such as rectangles, triangles, lines, Arcs and quadratic and cubic curves and path 2d objects.
## Applying styles and colors
The most important properties to apply colors to shapes are**fillStyle** and **strokeStyle**. The first uses filling shapes and the second uses filling outlines. And these two properties are set to black by default, and when applying these properties the default disapears and the new values are used.

## Drawing text
For rendering text, there are two methods, **fillText**and **strokeText**. For styling text, it uses the same properties as CSS sich as font and text-align and text base line.