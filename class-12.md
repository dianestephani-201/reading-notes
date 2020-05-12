# Class 12
### Article: Animated Charts with Chart.js
- Chart.js is a JavaScript plugin that uses HTML5's canvas element to draw a graph onto a page.
- Bar charts, pie charts, line graphs, etc.

### Canvas API
- The canvas element has only 2 attributes, width and height. Both are optional and can be set using DOM properties. The default size is 300 x 150 px.
- Make a habit of supplying an ID to a canvas element, as it will be easier to identify in a script.
- Canvas more easily defines **fallback content:** makes the canvas more accessible for older browsers, etc. Fallback content is displayed in browsers that don't support Canvas.
- This element has a method called getContext() that takes one parameter: the type of context. For 2D graphics, specify '2d.'
- **The coordinate space** is the canvas grid. 1 unit in the grid corresponds to 1 pixel on the canvas. Elements are placed relative to coordinate (0,0), the **origin.**
- Canvas supports rectanges and paths (lists of points connected by lines).
- FillStyle and strokeStyle apply colors to a shape. 
- Text can be rendered using fillText or strokeText.