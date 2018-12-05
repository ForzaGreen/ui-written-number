# ui-written-number
UI to convert numbers to words

https://forzagreen.github.io/ui-written-number/

## JS Converter
This uses the [js-written-number](https://github.com/yamadapc/js-written-number) library to convert number to text.
To require it from the browser, the [Browserify](http://browserify.org/) tool is used:
```
$ browserify main.js -o bundle.js --s written-number
```
with `main.js` containing: 
```
var writtenNumber = require('written-number');
module.exports = writtenNumber;
```
## UI
[Bootswatch](https://bootswatch.com/), which is based on the [Bootstrap](http://getbootstrap.com/) framework.
The flags are from [flag-icon-css](https://github.com/lipis/flag-icon-css) library.

## MVC Controller
The Controller in the app is [Vue.js](https://vuejs.org/).

## License
MIT
