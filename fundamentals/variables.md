# Variables

## Variable naming

There are two limitations on variable names in JavaScript:

1. The name must contain only letters, digits, or the symbols `$` and `_`.
2. The first character must not be a digit.

When the name contains multiple words, [camelCase](https://en.wikipedia.org/wiki/CamelCase) is commonly used. That is: words go one after another, each word except first starting with a capital letter: `myVeryLongName`.

:bulb:Case matters!



## Constant 

Variables declared using `const` are called “constants”. They cannot be reassigned. An attempt to do so would cause an error

### Uppercase constants

There is a widespread practice to use constants as aliases for difficult-to-remember values that are ***known before execution***

```javascript
const COLOR_RED = "#F00";
```

:question:When should we use capitals for a constant and when should we name it normally? 

Being a “constant” just means that a variable’s value never changes. But some constants are known before execution and some constants are *calculated* in run-time, during the execution, but do not change after their initial assignment.
