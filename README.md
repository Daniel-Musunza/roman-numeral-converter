# Roman Numeral Converter

This is a JavaScript function that converts Arabic numerals to Roman numerals. It takes a given number as input and returns the corresponding Roman numeral representation.

## Usage

To use the Roman Numeral Converter function, follow these steps:

1. Copy the `convertToRoman` function into your JavaScript project.
2. Call the `convertToRoman` function and pass the desired number as an argument.
3. The function will return the Roman numeral representation of the input number.

```javascript
// Example usage
console.log(convertToRoman(36)); // Output: XXXVI
```
Make sure you have a JavaScript runtime environment (e.g., a web browser or Node.js) to run the code.

## Function Description
The `convertToRoman` function takes the following parameter:

- `num` (required): The Arabic numeral to be converted to a Roman numeral.

The function uses a loop and an array of Roman numeral symbols and their corresponding values. It iterates through the array, checking if the current value is less than or equal to the given number (num). If it is, it appends the corresponding Roman numeral symbol to the output string and subtracts the value from num. The process continues until num is reduced to zero.

The function then returns the resulting Roman numeral.

## Example

```javascript
console.log(convertToRoman(36)); // Output: XXXVI

```

This example demonstrates converting the number 36 to its Roman numeral representation, which is "XXXVI".

## Limitations
The `convertToRoman` function is designed to handle positive integers up to 3999, which is the upper limit of Roman numerals. Attempting to convert numbers outside this range may result in unexpected behavior.

## Credits
This code was implemented based on the Roman numeral system and the rules for conversion.

## License
This code is released under the MIT License.
