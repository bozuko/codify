Codify lets you transform integers to base36 strings and vice versa. All strings use uppercase letters.

## Example

    var codify = require('codify');
    var code = codify.toCode(10); // 'A'
    var testInt = codify.toInt(code);