## JavaScript Basics

### Variables: `var`, `let`, `const`
JavaScript offers three variable declaration options: `var`, `let`, and `const`. Choose `var` for global variables, `let` for block-scoped variables, and `const` for constants that remain unchanged.

### MDN Documentation
Explore the extensive and regularly updated JavaScript documentation on the Mozilla Developer Network (MDN): [MDN JavaScript Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

### Strings
Utilize the `for...of` loop for iterating through characters in a string:
```javascript
for (let char of str) {
  // Your code here
}
```

## Objects (Dictionaries)
Use the `for...in` loop to iterate through keys in an object:

```javascript
for (let key in obj) {
  // Your code here
}
```
## Printing
Print variables or values using template literals:

```javascript
console.log(`${item}`);
```

## Arrays
### Manipulate arrays with shift for deleting an element from the start and unshift for adding an element to the start.
```javascript
// Delete an element from the start of the array
array.shift();

// Add an element to the start of the array
array.unshift(newValue);
```

## Higher Order Functions

In programming, **higher-order functions** are functions that either take one or more functions as arguments or return a function as their result. They are a powerful concept in functional programming and provide a flexible way to work with functions.

### forEach

- **Description:** Iterates over each element of an array and applies a provided function to each element.
- **Example:**
  ```javascript
  const numbers = [1, 2, 3, 4];
  numbers.forEach((num) => console.log(num * 2));
  // Output: 2, 4, 6, 8
  ```
  
### map

- **Description:** Creates a new array with the results of calling a provided function on every element in the array.
- **Example:**
  ```javascript
  Copy code
  const numbers = [1, 2, 3, 4];
  const doubled = numbers.map((num) => num * 2);
  // doubled: [2, 4, 6, 8]
  ```
### filter

**Description:** Creates a new array with all elements that pass the test implemented by the provided function.

**Example:**
```javascript
const numbers = [1, 2, 3, 4];
const evenNumbers = numbers.filter((num) => num % 2 === 0);
// evenNumbers: [2, 4]
```

### Reduce

**Description**: Applies a function against an accumulator and each element in the array (from left to right) to reduce it to a single value.
**Example:**
```javascript
Copy code
const numbers = [1, 2, 3, 4];
const sum = numbers.reduce((acc, num) => acc + num, 0);
// sum: 10
```
These higher-order functions are commonly used for their conciseness, readability, and the ability to create more expressive and declarative code.
