### JS Arrays

- An array is a special variable, which can hold more than one value:

```javascript
const cars = ["Audi", "Volvo", "BMW"];
```

### Why use an array?

- If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

```javascript
let car1 = "Audi";
let car2 = "Volvo";
let car3 = "BMW";
```

- However, what if you want to loop through the cars and find a specific one? And what if you had not 3 cars, but 300?
- The solution is an array!
- An array can hold many values under a single name, and you can access the values by referring to an _index_ number.

### Creating an array

- Using an array literal `[]` is the easiest way to create a JavaScript Array.
- Syntax:

```javascript
const array_name = [item1, item2, ...];
```

> It is a common practice to declare arrays with the const keyword.

### Example

```javascript
const cars = ["Audi", "Volvo", "BMW"];
```

```javascript
// empty array
const myList = [];

// array of numbers
const numberArray = [2, 4, 6, 8];

// array of strings
const stringArray = ["eat", "work", "sleep"];

// array with mixed data types
const newData = ["work", "exercise", 1, true];
```

- You can also create an array, and then provide the elements:

```javascript
const cars = [];
cars[0] = "Audi";
cars[1] = "Volvo";
cars[2] = "BMW";
```

### Using the JS Keyword - _new_

- The following example also creates an Array, and assigns values to it:

```javascript
const cars = new Array("Audi", "Volvo", "BMW");
```

### Accessing Array elements

- You access an array element by referring to the **index number**:

```javascript
const cars = ["Audi", "Volvo", "BMW"];
let myCar = cars[0];
```

- Array indexes start with `0`
- `[0]` is the first element. `[1]` is the second element.

### Changing Array elements

- You can also add or change the elements by accessing the index value.

```javascript
const cars = ["Audi", "Volvo", "BMW"];
cars[0] = "Opel";

console.log(cars); // [ 'Opel', 'Volvo', 'BMW' ]
```

```javascript
let dailyActivities = ["eat", "sleep"];

// this will add the new element 'exercise' at the 2 index
dailyActivities[2] = "exercise";

console.log(dailyActivities); // [ 'eat', 'sleep', 'exercise' ]
```

- Suppose, an array has two elements. If you try to add an element at index 3 (fourth element), the third element will be undefined. For example:

```javascript
let dailyActivities = ["eat", "sleep"];

// this will add the new element 'exercise' at the 3 index
dailyActivities[3] = "exercise";

console.log(dailyActivities); // [ "eat", "sleep", undefined, "exercise" ]
```

### Array Length

You can find the length of an element (the number of elements in an array) using the `length` property.

```javascript
const dailyActivities = ["eat", "sleep"];

// this gives the total number of elements in an array
console.log(dailyActivities.length); // 2
```
---

### Challenges

- Write a JavaScript program to compute the sum and product of an array of integers.
- Write a function `printNumbers(arr)` that takes an array as a parameter and prints the elements in the array on a new line. _Elements in `arr` can be of any data type (integers, float, strings)_
