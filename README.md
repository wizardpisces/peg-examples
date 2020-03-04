# peg-examples
peg.js (Parser Generator for JavaScript) related examples


# how to run

simply [use online version](https://pegjs.org/online)

1. paste *.pegjs file to the Grammar 
2. paste related input.* file to Test

the output will be the same as output.*

Or

follow [peg.js documentation](https://pegjs.org/documentation) to set local enviroment
```js
npm install -g pegjs

//generate dist file example
pegjs -o dist/cssParser.js css_parser.pegjs
```

