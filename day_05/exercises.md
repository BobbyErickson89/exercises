## Knowledge Based

- Student can explain the phrase: “zero indexed”
- Student can explain how the Window object is connected to all JavaScript objects in an active web page

#### Questions

1. When looking at an array, do we say the first element is at position 1? Why or why not?
2. Look at the following array and answer the following:
  - Which name is at position 2 - `names[2]`?
  - Which name is at position 0 - `names[0]`?
  - Which name is at position 5 - `names[5]`?

```js
var names = ["Sam", "Jessica", "Peter", "Mason", "Eric"];
```

3. If I opened up the Chrome console and ran the following line of code, what object does the variable `firstName` get attached to? Explain your answer.

```js
var firstName = "Princess";
```

## Skill Based

- Student can identify and create object literals
- Students can access and edit object literal data using dot notation
- Student can call existing functions that take parameters and return values to alter the state of a program.


#### Exercise 1

Read the following description of an animal and create an object named `animal` based on all the details in the description. Your object should contain the following:

- name
- age
- location
- foods
- hobbies

_Elle the elephant is 6 years old and is currently living at the Wildlife Trust. She loves to eat tomatoes and corn on the cob. Her hobbies include laying in the sun and swimming in the pond._

---

```js
var animal = {
  name: 'Elle',
  age: 6,
  location: 'Wildlife Trust',
  foods: ['Tomatoes', 'Corn on the Cob'],
  hobbies: ['laying in the sun', 'swimming in the pond']
}
```

#### Exercise 2

Copy the following code into a file called `main.js` and log to the console the following answers.

1. Log the price
2. Log the title
3. Log the third tag listed in tags
4. Log the image URL.
5. Log the first category

```js

var productData = {
  state: "active",
  title: "Mid Century Siesta Ware White Mug with Anchor",
  price: 12.00,
  quantity: 1,
  tags: ["mug", "siesta ware", "beer mug", "white glass mug", "anchor and stars"],
  category_path: ["Vintage", "Housewares", "Cup"],
  image: {
    small: {
      url: "http://placehold.it/300x300"
    }
  }
};
```

#### Exercise 3

Copy the following block of code to your `main.js` file and write 2 statements for each function and log the results.


```js
// Get the sum of two numbers
function sum (x, y) {
  return x + y;
}
// Find the largest of two numbers
function max(a, b){
  var largest;
  if (a > b) {
    largest = a;
  } else {
    largest = b;
  }
  return largest;
}
```


#### Exercise 4 (HARD MODE)

Take a look at the following code example and the errors so that the function returns the proper answer (10).

```js

function math (num1, num2, operator) {
  var answer;

  if (operator === "+") {
    answer = num1 - num2;
  } else if (operator === "-") {
    answer = num1 - num2;
  } else if (operator = "/") {
    answer = num1 / num2;
  } else if (operator === "*") {
    answer = num1 * num2;
  }

  return answer;

}

console.log(math(5, 2, "+")); // 7
console.log(math(5, 2, "-")); // 3
console.log(math(5, 2, "*")); // 10
console.log(math(5, 2, "/")); // 2.5

```