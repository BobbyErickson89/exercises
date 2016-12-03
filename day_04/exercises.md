## Knowledge Based

- Student can identify the term “Operator”
- Student can list and explain the 5 primitives in JavaScript.
- Student can explain the components of an expression
- Student can identify expressions present in an existing JavaScript program

#### Questions

1. Define the term `operator` and explain what their purpose is in JavaScript.
2. Please list the five primitives types in JavaScript.
3. Take a look at the table below and identify the primitive types next to each one.
4. Write a short sentence explaining how expressions work and why they are useful in JavaScript.

| What Primitive Type is this? | Answer |
| ---- | ---- |
| `45` |    |
| `"I heart JS"` |    |
| `'Pizza is life'` |    |
| `3.14` |    |
| `true` |    |
| `" "` |    |
| `false` |    |
| `'5,5555'` |    |

## Skill Based

- Student can appropriately use:
  - Assignment
  - Equality
  - Concatenation
  - Math (`+`,`-`,`/`,`*`)
- Student can convert logical statements into algorithms using “if”, “if else” statements
- Student can read and interpret common runtime errors in the console.
- Student can use “console.log” to help them develop and debug the state of their programs

#### Exercise 1

Copy the contents below into a file named `main.js` and read through each exercise and provide the answers or code required. You should use `console.log` to help test your code.

```js
/*=========================================================
    Part 1: Variables
*/
var givenName;
// Q: What value is stored in `givenName` right now?
// A:


givenName = "Brett";
// Q: What is `givenName` set to now?
// A:


givenName = givenName;
// Q: What is `givenName` set to now?
// A:

```

#### Exercise 2

Using the above code, create a variable called `greeting` that will store the expression below with `givenName` being used. You should use `console.log` to help test your code.

The final output should look like: `Hello, how are you Brett?`


#### Exercise 3

Copy the contents below into your file named `main.js` and read through each exercise and provide the answers or code required. You should use `console.log` to help test your code.

```js
/*=========================================================
     Part 2: Simple Math
*/
var high = 50;
var low  = 10;


var math = high - low;
// Q: What is `math` set to?
// A:

math = high - "5";
// Q: What is `math` set to?
// A:


// Using the `high` & `low` Variables, work through each of the 4 math operators below and log the answers to the console.
// Write Code Below:

```

#### Exercise 4

Copy the contents below into your file named `main.js` and read through each exercise and provide the answers or code required. You should use `console.log` to help test your code.

```js
/* =========================================================
     Part 3: Expressions
*/


// Create a variable to calculate your age
// The answer should read "NAME is XX years old"
// The answer should not be written in a comment.
var born = 1900;
var today = 1900;

// Answers Below:



// Store some information following in variables.
var yourName;
var instructorName;

// Update the variables above so the expression reads correctly.
// Answers Below:


// Final Statement
var statement = yourName + " is taking a class at The Iron Yard, my instructor's name is " + instructorName;
```

#### Exercise 5

Take the following two variables:

```js
var myAge = 45;
```

Write a conditional statement that will test if an age is over 100. If it is set a variable `isOld` to `true` otherwise set it to `false`.


#### Exercise 6

Each of the following blocks of JavaScript contains errors. Take a look at each and do the following:

1. Identify which line the error occurs on.
2. Explain the cause of the error
3. Fix the error, so the code produces the desired response.

```js
var firstName = "Julia";
var lastName = "Roberts";
var fullName = firstName + lastname;

console.log(fullName); // Julia Roberts
```

```js
var yearBorn = 1975;
var currentYear = 2016;
Var age = currentYear - yearBorn;

console.log(age); // 41
```