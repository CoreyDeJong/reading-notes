### Easily create stunning animated charts with chart.js
 - Charts.js is a javascript plugin that makes charts easy
 - ``<canvas>`` is the element within HTML and requires ``<script>`` to js.
 - you can create line, bar and pie charts

 ### Basic Usage
 - a closing tag ``</canvas>`` is required eventhough similar ``<img>`` tags do not require a closing tag.
 - ``<canvas>`` elment has a method called ``getContext()`` to obtain the rendering context and its drawing functions:
     - ``var canvas = document.getElementById('tutorial');``
     - ``var ctx = canvas.getContext('2d');``

### Drawing Shapes With Canvas
 - __x, y coordinates__ are used with x=0, y=0 being the top left of the grid and x increasing left to right and y-axis increasing top to bottom.
 - __Rectangles__
    - Draws a filled rectangle.
        - fillRect(x, y, width, height)
    - Draws a rectangular outline.
        - strokeRect(x, y, width, height)
    - Clears the specified rectangular area, making it fully transparent.
        - clearRect(x, y, width, height)
 - __function draw(){}__ is the function used to draw the parameters.
 - __Paths__ is a line or curve given it connects multiple points
    - __lineTo(x, y)__ is to draw a straight line
 - __Arcs__ ``arcTo(x1, y1, x2, y2, radius)``
 - __Rectangles__ ``rect(x, y, width, height)``

 ### Applying Styles and Colors
 - Sets the style used when filling shapes.
    - fillStyle = color
 - Sets the style for shapes' outlines.
    - strokeStyle = color
 - Sets the width of lines drawn in the future.
    - lineWidth = value
 - __Line ends__
    - __butt__ The ends of lines are squared off at the endpoints.
    - __round__ The ends of lines are rounded.
    - __square__ The ends of lines are squared off by adding a box with an equal width and half the height of the line's thickness.
 - __Repeat__
    - __repeat__ Tiles the image in both vertical and horizontal directions.
    - __repeat-x__ Tiles the image horizontally but not vertically.
    - __repeat-y__ Tiles the image vertically but not horizontally.
    - __no-repeat__ Doesn't tile the image. It's used only once.
 - __Shadows__
    - __shadowOffsetX = float__     Indicates the horizontal distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.
    - __shadowOffsetY = float__    Indicates the vertical distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.
    - __shadowBlur = float__    Indicates the size of the blurring effect; this value doesn't correspond to a number of pixels and is not affected by the current transformation matrix. The default value is 0.
    - __shadowColor = color__    A standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black.

### Drawing Text
 - __Drawing Text__
    - Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
        - fillText(text, x, y [, maxWidth])
    - Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw
         - strokeText(text, x, y [, maxWidth])