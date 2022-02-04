### Conditional Statements
- Conditional statements are used to perform different actions based on different conditions.
- We have the following conditional statements:
	* Use `if` to specify a block of code to be executed, if a specified condition is `true`
	* Use `else` to specify a block of code to be executed, if the same condition is `false`
	* Use `else if` to specify a new condition to test, if the first condition is `false`

Here are a few examples,

- `If`
```javascript
let number = 8;

if (number < 10) {
	console.log("Number is less than 10")
}

// Number is less than 10
```

- `If-Else-if`
```javascript
let number = 8;

if (number < 7) {
	console.log("Number is less than 10");
} else if (number > 6) {
	console.log("Number is greater than 8");
}

// Output: Number is greater than 8
```

- `If-else`
```javascript
let number = 8;

if (number < 8) {
	console.log("Number is less than 10");
} else if (number > 8) {
	console.log("Number is greater than 6");
} else {
	console.log("Number is definitely equal to 8");
}

// Output: Number is definitely equal to 8
```


### Challenges

- Write an if-elif-else chain that determines a person’s stage of life. Set a value for the variable age, and then:
	* If the person is less than 2 years old, print a message that the person is a baby.
	* If the person is at least 2 years old but less than 4, print a message that the person is a toddler.
	* If the person is at least 4 years old but less than 13, print a message that the person is a kid.
	* If the person is at least 13 years old but less than 20, print a message that the person is a teenager.
	* If the person is at least 20 years old but less than 65, print a message that the person is an adult.
	* If the person is age 65 or older, print a message that the person is an elder.
