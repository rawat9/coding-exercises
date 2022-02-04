### Functions
- A function is a block of code designed to perform a certain task.
- A function is defined with the function keyword, followed by a *name*, followed by *parentheses* ().
- The function may include parameter separated by commas, such as (*parameter1*, *parameter2*, ..)
- The code to be executed, by the function, is placed inside curly brackets: {}

Here is an example,

```javascript
function add(x, y) {
	return x + y;      // Function returns the sum of two numbers x & y
}
```

After calling the function,
```javascript
let result = add(2, 3);    // Function is called and result is stored in variable "result"
console.log(result);       // Prints 5
```


### Challenges

- Write a function that takes two numbers and returns the largest number of the two.

- Write a function that takes two numbers and returns the smallest number of the two.

- Write a function that takes a price (number) and a discount value (percentage) and returns the final price.

- Write a function that takes a string and returns only the first and last characters.
