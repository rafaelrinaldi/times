# n-times

> Run a function 𝘕 times

## Install

```sh
$ npm install n-times --save
```

## Usage

```js
const times = require('n-times');
const beep = bop => { console.log(bop); };

times(3, beep, 'yadda');
// => yadda
// => yadda
// => yadda
```

## API

## `times(n, fn, ...args)`

### `n`

*Required*  
Type: `integer`  

Number of times to run a function.

### `fn`

*Required*  
Type: `function`  

Function to run N times.  
Receives the value of current iteration as the last parameter.

#### `...args`

Type: `arguments`  
Default: `false`  

List of arguments to pass to `fn` on every call.

## License

MIT © [Rafael Rinaldi](http://rinaldi.io)
