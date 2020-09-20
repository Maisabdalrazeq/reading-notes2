# Welcome To The Read12 Page ...


**What Is The Chart??**

*Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.*

![img](https://i.stack.imgur.com/642Ei.png)


**How To Creating a Chart?**

*It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas> `node to render the chart.*

1. Setting up:

**The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:*

`<!DOCTYPE html>`
`<html lang="en">`
 `   <head>`
        `<meta charset="utf-8" />`
        `<title>Chart.js demo</title>`
        `<script src='Chart.min.js'></script>`
    `</head>`
    `<body>`
    `</body>`
`</html>`

2. Drawing a line chart:

*To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:*

`<canvas id="buyers" width="600" height="400"></canvas>`

*Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:*

`<script>`
   ` var buyers = document.getElementById('buyers').getContext('2d');`
   ` new Chart(buyers).Line(buyerData);`
`</script>`

3. Drawing a pie chart:

*Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:*

`<canvas id="countries" width="600" height="400"></canvas>`

4. Drawing a bar chart:

*Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:*

`<canvas id="income" width="600" height="400"></canvas>`


**The `<canvas>` element..**

*At first sight a `<canvas> `looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.*

**How to Applying styles and colors?**


*Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: **fillStyle** and **strokeStyle**.*

- fillStyle = color :
Sets the style used when filling shapes.

- strokeStyle = color:
Sets the style for shapes' outlines.

***Example:***

`// these all set the fillStyle to 'orange'`

`ctx.fillStyle = 'orange';`
`ctx.fillStyle = '#FFA500';`
`ctx.fillStyle = 'rgb(255, 165, 0)';`
`ctx.fillStyle = 'rgba(255, 165, 0, 1)';`


***A fillStyle example:***

`function draw() {`
 ` var ctx = document.getElementById('canvas').getContext('2d');`
  `for (var i = 0; i < 6; i++) {`
   ` for (var j = 0; j < 6; j++) {`
    `  ctx.fillStyle = 'rgb(' + Math.floor(255 - 42.5 * i) + ', ' +`
     `                  Math.floor(255 - 42.5 * j) + ', 0)';`
      `ctx.fillRect(j * 25, i * 25, 25, 25);`
    `}`
  `}`
`}`


***A strokeStyle example:***

`function draw() {`
  `  var ctx = document.getElementById('canvas').getContext('2d');`
   ` for (var i = 0; i < 6; i++) {`
     ` for (var j = 0; j < 6; j++) {`
      `  ctx.strokeStyle = 'rgb(0, ' + Math.floor(255 - 42.5 * i) + ', ' + `
        `                 Math.floor(255 - 42.5 * j) + ')';`
        `ctx.beginPath();`
      `  ctx.arc(12.5 + j * 25, 12.5 + i * 25, 10, 0, Math.PI * 2, true);`
      `  ctx.stroke();`
     ` }`
  `  }`
 ` }`

**Drawing text**

*The canvas rendering context provides two methods to render text:*

- fillText(text, x, y [, maxWidth]):
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

- strokeText(text, x, y [, maxWidth]):
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.