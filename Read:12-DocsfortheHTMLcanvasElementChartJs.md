# Chart.js API

    A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

    The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options listed in the documentation.

# Chart.js docs

    It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.

    In this example, we create a bar chart for a single dataset and render that in our page. You can see all the ways to use Chart.js in the usage documentation.

# Read the following articles on the Canvas API.
    ## Basic usage
        At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

    ## Drawing shapes with canvas
        Unlike SVG, <canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.
        First let's look at the rectangle. There are three functions that draw rectangles on the canvas:
        **fillRect(x, y, width, height)**
        Draws a filled rectangle.
        **strokeRect(x, y, width, height)**
        Draws a rectangular outline.
        **clearRect(x, y, width, height)**
        Clears the specified rectangular area, making it fully transparent.

    ## Applying styles and colors
        Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
        fillStyle = color
        Sets the style used when filling shapes.
        strokeStyle = color
        Sets the style for shapes' outlines.
        color is a string representing a CSS <color>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).

    ## Drawing text
        The canvas rendering context provides two methods to render text:
        fillText(text, x, y [, maxWidth])
        Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
        strokeText(text, x, y [, maxWidth])
        Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.