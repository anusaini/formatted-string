# format-string

Formatting a string based upon the object passed.

## Usage

```javascript

    const format = require('@anu/format-string')

    const str = formatted("{a} is {b}; {b} is {a}", {a:'red', b: 'blue'})

    console.log(str);

    // output
    "red is blue; blue is red"

```

## License

MIT &copy; Anubhav Saini 2016 2017 2018

## History

Forked from formatted-string.
