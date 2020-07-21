# Paul's Reading Notes

## Code 201

### Class 12: Docs for the HTML <canvas> Element & Chart.js

**Reading Material for the Assignment**
1. Articles on Chart.js
- [Chart.js API](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
- [Chart.js docs](http://www.chartjs.org/docs/)
2. Articles on Canvas API
- [Basic Usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
- [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
- [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
- [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)



#### Articles on Chart.js
##### - [Chart.js API](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
##### [Chart.js docs](http://www.chartjs.org/docs/)

Chart.js is a JavaScript plugin that can draw bar, line, and pie charts.  These charts can be added to a webpage using the HTML5 canvas element.

*Example of Drawing a Line Graph*
- copy the script link to your HTML head `<script src='Chart.min.js'></script>`
- create a canvas element in your HTML body to draw the chart in `<canvas id="here" width="600" height="400"></canvas>`
- add script calls to the foot of the body
`<script>
  var buyers = document.getElementById('buyers').getContext('2d)';
  new Chart(buyers).Line(buyerData);
</script>`
- also within the script call, data, labels, and formatting must be provided



#### Articles on Canvas API

##### [Basic Usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
##### [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
##### [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
##### [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

- Canvas is an HTML element
- Its tag is `<canvas>`
- It only has two attributes, which are both optional: width and height
- Syntax to create a canvas element: `<canvas id="here" width="600" height="400"></canvas>`
- canvas element can be identified and styled like using global attributes such as id, class, margin, border, etc.
- can have fallback content to display if the user's browswer does not support canvas
- canvas element has both opening and closing tags


[Return to Table of Contents for Paul's Reading Notes](https://paul-leonard.github.io/reading-notes/ "Go back to find more notes!")



---



Thank you for visiting my page of notes.  I hope they were helpful to you.  Please also check out [my GitHub portfolio page](https://github.com/paul-leonard "Paul's GitHub Portfolio").