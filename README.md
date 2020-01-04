# @spudly/range

Creates a range of numbers

# Installation

```bash
npm install --save @spudly/range
```

# Usage

```js
import range from '@spudly/range';

range(-3, 3); // => [-3, -2, -1, 0, 1, 2]
range(3, -3); // => [3, 2, 1, 0, -1, -2]
range(0, 1, 0.1); // => [0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9]
```
