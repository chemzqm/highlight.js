# highlight.js

  [highlight.js](http://softwaremaniacs.org/soft/highlight/en/) for component.

  [Demo](http://chemzqm.github.io/highlight.js/index.html)

## Installation

  Install with [component(1)](http://component.io):

    $ component install chemzqm/highlight.js

## API

### hljs.highlight(lang, code)

Highlight the `code` with `lang`.

### hljs.highlightAuto(text)

Highlight the `text` with language auto detect.

## Example

``` js
var hljs = require('highlight.js');
var code = "var index = 123;\n var foo ='bar'\n";
var res = hljs.highlight('javascript', code);
//get the result code
console.log(res.value); 
```

## License

  MIT
