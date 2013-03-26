# svg.clock.js

A clock build with [svg.js](https://github.com/wout/svg.js), inspired by the swiss railway clock, designed by Hans Hilfiker.

Svg.clock.js is licensed under the terms of the MIT License.

## Usage
Include this plugin after including the svg.js library in your html document.

Then fire up the clock:

```javascript
var draw = SVG('canvas').size(400, 400)
var clock = draw.clock('100%')
```

## Dependencies
- [svg.js](https://github.com/wout/svg.js)
- [svg.easing.js](https://github.com/wout/svg.easing.js)