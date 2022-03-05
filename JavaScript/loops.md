### Loops
- Loops can execute a block of code a number of times.
- JavaScript supports different kinds of loops:
	* `for` - loops through a block of code a number of times
	* `for/in` - loops through the properties of an object
	* `for/of` - loops through the values of an iterable object
	* `while` - loops through a block of code while a specified condition is true
	* `do/while` - also loops through a block of code while a specified condition is true


### Syntax
```javascript
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```

- Statement 1 is executed (one time) before the execution of the code block.
- Statement 2 defines the condition for executing the code block.
- Statement 3 is executed (every time) after the code block has been executed.


### Example
```javascript
for (let i = 0; i < 5; i++) {
	console.log(i);
}
```
> Output
```
0
1
2
3
4
```

### Challenges
- Write a program to print numbers from 1 to 10.
- Write a program to print number from 10 to 1.
- Write a program to calculate the sum of first 10 natural number.
- Write a program to compute the number of odd numbers between two numbers `a` and `b`.

