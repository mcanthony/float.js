## float.js

A little mirror class for introspecting the bit-patterns of floating-point numbers using typed arrays.

Example:

``` javascript
Math.PI.introspect().mantissa;     //             1001001000011111101101010100010001000010110100011000
Math.E.introspect().exponent;      //   10000000000
(9.0).introspect().toBitString();  // 0100000000100010000000000000000000000000000000000000000000000000
(-Math.PI).introspect().negative;  // true
```

## License

Copyright © 2012 Dave Herman

Licensed under the [MIT License](http://mit-license.org).
