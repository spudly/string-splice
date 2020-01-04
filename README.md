# @spudly/string-splice

Like Array.prototype.splce, except it operates on strings.

# Installation

```bash
npm install --save @spudly/string-splice
```

# Usage

```js
import stringSplice from '@spudly/string-splice';

stringSplice(4, 1, '', 'Hello World!'); // => 'Hell World!'
stringSplice(1, 0, 'ave fun at J', 'Hello World!'); // => 'Have fun at Jello World!'
stringSplice(0, 2, 'Marshma', 'Hello World!'); // => 'Marshmallo World!
stringSplice(25, 5, ' We meet again!', 'Hello World!'); // => 'Hello World! We meet again!'
stringSplice(-1, 1, '?', 'Hello World!'); // => 'Hello World?'
stringSplice(-25, 1, 'C', 'Hello World!'); // => 'Cello World!'
stringSplice(3, -15, 'p save Tange', 'Hello World!'); // => 'Help save Tangelo World!'
stringSplice(0)(2)('Marshma')('Hello World!'); // => 'Marshmallo World!'
```
