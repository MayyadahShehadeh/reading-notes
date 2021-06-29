# Chart.js, Canvas
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

- Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

><*canvas id="buyers" width="600" height="400"*><*/canvas*>

- Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:
><*script*>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
<*/script*>

## canvas
At first sight a <*canvas*> looks like the <*img*> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <*canvas*> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.


- **Colors**

Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: *fillStyle* and *strokeStyle*.

***fillStyle = color***
Sets the style used when filling shapes.

***strokeStyle = color***
Sets the style for shapes' outlines.

color is a string representing a CSS <*color*>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).

- **Drawing text**

The canvas rendering context provides two methods to render text:

***fillText(text, x, y [, maxWidth])***
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

***strokeText(text, x, y [, maxWidth])***
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

---------------------
&copy; Sorces: 
- [Chart.js docs](https://www.chartjs.org/docs/latest/)
- [Basic usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
- [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
- [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

