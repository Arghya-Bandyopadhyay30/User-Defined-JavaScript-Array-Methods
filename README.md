# User-Defined JavaScript Array Methods

This repository contains user-defined JavaScript functions for common array methods. These custom functions replicate the functionality of their built-in counterparts (`map`, `filter`, `reduce`, `forEach`) but do not use the `Array.prototype` methods. Instead, they accept an array as input and provide the same basic functionality. Each method is implemented in a separate JavaScript file, and each file includes necessary test cases to demonstrate the required functionality.

## Contents

- [myMap.js](myMap.js): Custom implementation of the `map` method.
- [myFilter.js](myFilter.js): Custom implementation of the `filter` method.
- [myReduce.js](myReduce.js): Custom implementation of the `reduce` method.
- [myForEach.js](myForEach.js): Custom implementation of the `forEach` method.

## Usage

To use these custom functions, follow these steps:

1. Clone or download this repository to your local machine.

2. Include the JavaScript file corresponding to the function you want to use in your project.

3. Use the custom function as you would use the built-in function, passing an array as an argument.

4. Refer to the provided test cases within each JavaScript file to see examples of how to use the custom function and the expected output.

## Example Usage

Here's an example of how to use the custom `myMap` function:

```javascript
// Include the custom myMap function
const myMap = require('./myMap');

// Sample array
const numbers = [1, 2, 3, 4, 5];

// Use the custom myMap function to double each element in the array
const doubledNumbers = myMap(numbers, (value) => value * 2);

console.log(doubledNumbers); // Output: [2, 4, 6, 8, 10]
```

## Test Cases

Each JavaScript file includes a set of test cases to validate the functionality of the respective custom function. You can refer to these test cases to ensure that the custom function works as expected.

## Output Screenshots

Screenshots demonstrating the output of each user-defined function are also provided in this repository. You can refer to these screenshots for a visual confirmation of the custom functions' functionality.

![Results](https://github.com/Arghya-Bandyopadhyay30/User-Defined-JavaScript-Array-Methods/assets/64891347/65c1b20f-6036-4f08-92e5-f5cb4e9049b5)

## Contributions

Contributions and improvements to these custom functions are welcome. If you have any suggestions, bug fixes, or enhancements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this code in accordance with the terms of the license.

Enjoy using these custom array methods, and happy coding!
