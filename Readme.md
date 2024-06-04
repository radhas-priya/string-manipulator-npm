# string-manipulator

A simple library for common string manipulation operations.
  reverseString,
    capitalizeWords,
    toCamelCase,
    truncateString,
    isPalindrome,
    isAnagram,
    isPangram,
    toTitleCase,
    toKebabCase,
    toSnakeCase,
    removeVowels,
    countVowelsAndConsonants
    These all functions are available in this package

## Installation

```sh
npm install string-manipulator



# usage


```javascript
const {
    reverseString,
    capitalizeWords,
    toCamelCase,
    truncateString,
    isPalindrome,
    isAnagram,
    isPangram,
    toTitleCase,
    toKebabCase,
    toSnakeCase,
    removeVowels,
    countVowelsAndConsonants
} = require('string-manipulator');

// Example usage of functions
console.log(reverseString('hello')); // 'olleh'
console.log(capitalizeWords('hello world')); // 'Hello World'
console.log(toCamelCase('hello world')); // 'helloWorld'
// Add examples for other functions...

This ia an educational purpose package .User can download it and use its functionality in his projects.



## Functions

### `reverseString(str)`
Reverses a string.

### `capitalizeWords(str)`
Capitalizes the first letter of each word in a string.

### `toCamelCase(str)`
Converts a string to camel case.

###`truncateString(str)`
It truncates a string.

### ` isPalindrome(str)`
it checks that if the string is a palindrome or not.

### `isAnagram(str1, str2)`
It checks that if both strings are anagram of each other or not
### `isPangram(sentence)`
It check that if the sentece is a  pangram  or not

### `toTitleCase(str)`
It converts a string into titlecase
  hello world -----> Hello World

###`toKebabCase(str)`
It converts a string into kebab case
hello world -------> hello-world

### `toSnakeCase(str)`
It converts a string into snake case
Hello World ----> hello_world

### `removeVowels(str)`
It removes vowels from the string .
Hello World  ----> Hll Wrld


### ` countVowelsAndConsonants(str)`
It count all vowels and consonants in the string.

countVowelsAndConsonants('Hello World'))  ----->   { vowels: 3, consonants: 7 }




## License

This project is licensed under the MIT License .


#### Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to contribute.

