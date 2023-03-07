```js
const clockWise = (mat: number[][]) => {
  for (let r = 0; r < mat.length; r++) {
    for (let c = 0; c < r; c++) {
      // fyll i logiken som saknas här i for loopen.
    }
  }

  return mat.map((r) => r.reverse());
};
```