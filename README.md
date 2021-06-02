# Fabric Brushes

A collection of brushes for fabric.js (version 4 and up).

- Crayon
- Fur
- Ink
- Long Fur
- Marker
- Ribbon
- Shaded
- Sketchy
- Spray
- Squares
- Web

## Table of contents
- [Demo](#demo)
- [Getting started](#getting-started)
- [Options](#options)
- [Browser support](#browser-support)
- [Real world examples](#real-world-examples)
- [License](#license)

## [Demo](https://av01d.github.io/fabric-brushes/index.html)
[Click here](https://av01d.github.io/fabric-brushes/index.html) for a live demo of all brushes included in this fabric.js addon.

[<img src="https://av01d.github.io/fabric-brushes/img/brush.crayon.gif" alt="Crayon brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.fur.gif" alt="Fur brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.ink.gif" alt="Ink brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.longfur.gif" alt="Long fur brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.marker.gif" alt="Marker brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.ribbon.gif" alt="Ribbon brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.shaded.gif" alt="Shaded brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.sketchy.gif" alt="Sketchy brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.spray.gif" alt="Spray brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.squares.gif" alt="Squares brush" width="640" height="320">](https://av01d.github.io/fabric-brush)
[<img src="https://av01d.github.io/fabric-brushes/img/brush.web.gif" alt="Web brush" width="640" height="320">](https://av01d.github.io/fabric-brush)

## Getting started

### Installation

This is an addon for fabric.js, so... make sure you load fabric.js before you include this addon.

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/fabric.js/4.4.0/fabric.min.js"></script>
<script src="/path/to/dist/fabric.brushes.min.js"></script>
```
### Usage

Choose the brush you want to use and initialize it:
```html
<canvas id="canvas" width="800" height="600">
```

```js
const fabricCanvas = new fabric.Canvas('canvas', {
	isDrawingMode: true
});

fabricCanvas.freeDrawingBrush = new fabric.WebBrush(fabricCanvas, {width:1, color:'#000', opacity:1});
````

[⬆ back to top](#table-of-contents)

## Options

Here are the options for all types of brushes.

### CrayonBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.CrayonBrush(fabricCanvas,
{
	width: 30, // Width of brush
	color: '#000', // Color of brush
	opacity: 0.6 // Opacity of brush
});
```

### FurBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.FurBrush(fabricCanvas,
{
	width: 1, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

### InkBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.InkBrush(fabricCanvas,
{
	width: 30, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

### LongFurBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.LongFurBrush(fabricCanvas,
{
	width: 1, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

### MarkerBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.MarkerBrush(fabricCanvas,
{
	width: 1, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

### RibbonBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.RibbonBrush(fabricCanvas,
{
	width: 1, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

### ShadedBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.ShadedBrush(fabricCanvas,
{
	width: 1, // Width of brush
	color: '#000', // Color of brush,
	shadeDistance: 1000, // Shade distance
	opacity: 1 // Opacity of brush
});
```

### SketchyBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.SketchyBrush(fabricCanvas,
{
	width: 1, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

### SprayBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.SprayBrush(fabricCanvas,
{
	width: 30, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

### SquaresBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.SquaresBrush(fabricCanvas,
{
	width: 1, // Stroke width of squares
	color: '#000', // Stroke color of squares
	bgColor: '#fff', // Background color of squares
	opacity: 1 // Opacity of brush
});
```

### WebBrush
```js
fabricCanvas.freeDrawingBrush = new fabric.WebBrush(fabricCanvas,
{
	width: 1, // Width of brush
	color: '#000', // Color of brush
	opacity: 1 // Opacity of brush
});
```

[⬆ back to top](#table-of-contents)

## Browser support

This addon works on the same browsers as fabric.js does:

- Firefox 4+
- Safari 5+
- Opera 9.64+
- Chrome (all versions)
- Edge (chromium based, all versions)
- IE11 and Edge legacy, supported but deprecated.

[⬆ back to top](#table-of-contents)

## Real world examples

The Fontpicker plugin is used (among others) on the following websites:

- [PosterMaker.com](https://www.postermaker.com/)

[⬆ back to top](#table-of-contents)

## License

This plugin is released under the MIT license. It is simple and easy to understand and places almost no restrictions on what you can do with the code.
[More Information](http://en.wikipedia.org/wiki/MIT_License).

The development of this component was funded by [Zygomatic](https://www.zygomatic.nl/).

[⬆ back to top](#table-of-contents)
