# datasets-cats
A dataset of about cats. Contains info on sex (M/F), body weight (kg), and heart weight (g) for 144 cats.

## installation

```
$ npm install --save datasets-cats
```
## usage

```js
var cats = require('datasets-cats');

cats.forEach(function(cat) {
  // each cat is an object like:
  // {
  //    sex: 'F',
  //    bodyWeight: 'BODY WEIGHT IN KILOGRAMS',
  //    heartWeight: 'HEART WEIGHT IN GRAMS',
  // }
  console.log(cat);
});

```

## credit

The data were obtained from

*Fisher, R.A. (1947) The analysis of covariance method for the relation between a part and the whole. Biometrics, 3, 65–68.*
