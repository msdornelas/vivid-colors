# vivid-colors
A small set of bold and bright colors for your project.

## Installation
```sh
npm install vivid-colors
```

## Basic usage
```js
const vividColors = require('vivid-colors');
```

## Color names
**These are the vivid colors you can choose:**
- black
- white
- auburn 
- burgundy
- cerise
- cerulean
- crimson
- gamboge
- limeGreen
- malachite
- mulberry
- orange
- orangePeel
- orchid
- raspberry
- red
- redTangelo
- skyBlue
- tangelo
- vermilion
- violet
- yellow

Color samples: [Click here](https://github.com/msdornelas/vivid-colors/blob/main/docs/colors.png?raw=true)

## How to use
- All color objects have the **ORIGINAL** property. This is the **default** color HEX code.
- All colors (**except BLACK and WHITE**) also have the **LIGHTER** and **DARKER** properties.

- The **LIGHTER** property will provide **5 lighter shades** of the chosen color.
- You can increase it from level **1** up to level **5**.

- The **DARKER** property will provide **5 darker shades** of the chosen color.
- You can increase it from level **1** up to level **5**.

- The **WHITE** color only has the additional property **DARKER**.
- The **BLACK** color only has the additional property **LIGHTER**.

## Example
```js
const vividColors = require('vivid-colors');

console.log(vividColors.black.original);
// Output: #000000

console.log(vividColors.black.lighter[4]);
// Output: #a2a2a2

console.log(vividColors.white.original);
// Output: #ffffff

console.log(vividColors.white.darker[1]);
// Output: #d0d0d0

console.log(vividColors.orchid.original);
// Output: #cc00ff

console.log(vividColors.orchid.lighter[1]);
// Output: #d952ff

console.log(vividColors.orchid.darker[2]);
// Output: #841ba2
```

## License
[MIT](LICENSE)
