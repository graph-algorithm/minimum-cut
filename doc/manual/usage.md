# Usage

The code needs a ES2015+ polyfill to work, for example
[regenerator-runtime/runtime](https://babeljs.io/docs/usage/polyfill).
```js
await import( 'regenerator-runtime/runtime.js' ) ;
// or
import 'regenerator-runtime/runtime.js' ;
```

Then
```js
const {mincut} = await import( '@aureooms/js-mincut' ) ;
// or
import {mincut} from '@aureooms/js-mincut' ;
```
