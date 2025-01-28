# is-def-npm-package

**is-def-npm-package** is a simple utility that checks if a given string is equal to `'DEF'`. This is my first npm package, designed to demonstrate the basic functionality of a string comparison.

## Installation

You can install the package via npm or yarn:

```bash
npm i @manojtharindu11/is-def
```

or

```bash
yarn add @manojtharindu11/is-def
```

## Usage

After installation, you can import the `isDef` function into your JavaScript code and use it to check if a string is `'DEF'`.

### Example

```javascript
const isDef = require("@manojtharindu11/is-def");

console.log(isDef("DEF")); // true
console.log(isDef("def")); // false
console.log(isDef("DEF123")); // false
console.log(isDef("")); // false
```

### Function Signature

```javascript
function isDef(value) {
  // Your implementation
}
```

### Parameters

- `value` (string): The string you want to check.

### Returns

- `true` if the value is exactly equal to `'DEF'`, otherwise `false`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
