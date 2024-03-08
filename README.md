
# isComply

## Overview

`isComply` is a lightweight JavaScript library for data validation. It provides simple functions to validate strings, numbers, emails, and dates.

## Installation

You can install `isComply` via npm:

```bash
npm install isComply
```
## Usage

```javascript
const isComply = require('isComply');

console.log(isComply.isString('Hello')); // true
console.log(isComply.isNumber(123)); // true
console.log(isComply.isEmail('example@email.com')); // true
console.log(isComply.isDate('2024-03-04')); // true
```

## API

### `isString(value)`

- `value`: The value to be validated.

Returns `true` if the value is a string, `false` otherwise.

### `isNumber(value)`

- `value`: The value to be validated.

Returns `true` if the value is a number, `false` otherwise.

### `isEmail(value)`

- `value`: The value to be validated.

Returns `true` if the value is a valid email address, `false` otherwise.

### `isDate(value)`

- `value`: The value to be validated.

Returns `true` if the value is a valid date string, `false` otherwise.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

