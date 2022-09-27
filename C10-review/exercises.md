# Exam Study Exercises

**Read before starting**
In Code-Labs, create a new folder called class-10. You will be working in the class-10 folder for today.

## Exercise 1:

- Create a folder inside of class-10 called exercise-1
- Inside exercise-1, create a file called [index.html](https://www.w3schools.com/html/)

Display 4 [images](https://www.w3schools.com/tags/tag_img.asp) of animals.

## Exercise 2:

- Create a folder inside of class-10 called exercise-2
- Inside exercise-1, create a file called index.html

Create a h1 with content of " 'Your name' Blog'.

For example,

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>John's Blog</h1>
  </body>
</html>
```

- Create a paragraph element with content of what your 'made up' blog is about.
- Create a div element with content of your favorite food.
- Create a span element with content of your favorite sport.

---

---

- Use CSS to color the background of your choosing
- Use CSS to color the text of your choosing
- Use CSS to give your h1 font size 50px
- Use CSS to center all your text

Include an image with height 300px and width 200px

## Exercise 3:

In the class-10 folder, create a folder called exercise-3.
Create a div with the class name center.

In the div, create a h1 with content 'Mary's Food Restaurant'.
For example,

```html
<div class="center">
  <h1>Marry's Food Restaurant</h1>
</div>
```

After the h1, create an h2 element with content 'Smoothies and Chicken Noodles'.

After the h2, create an [unordered list](https://www.w3schools.com/html/html_lists_unordered.asp).
Each list item should have a several menu items.

Last but not least, [center the div](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/)

## Exercise 4:

In the class-10 folder, create a folder called exercise-4.
Create a file called index.html.
Create a index.js file.

Link index.js to index.html like so with the script element:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <!-- Here -->
    <script src="./index.js"></script>
  </head>
  <body></body>
</html>
```

Use `console.log()` to log a number to the console. For example,

```js
console.log(10);
```

## Exercise 5:

In the class-10 folder, create a folder called exercise-5.
Create the necessary files to do the following:

In JavaScript, log to the console the following [data types](https://www.w3schools.com/js/js_datatypes.asp)

- number
- string
- boolean
- object
- array

## Exercise 6:

In the class-10 folder, create a folder called exercise-6.
Let's create some variables in JavaScript.

Here's an example,

Declare a let variable called firstName

```js
let firstName;
```

Initialize firstName to a string that represents a name.

```js
let firstName;
firstName = "John";
```

Log to the console fistName.

```js
let firstName;
firstName = "John";
console.log(firstName);
```

- Declare a variable called lastName
- Initialize lastName to your last name.
- log to the console lastName.

- Declare a variable called favoriteNumber;
- Initialize favoriteNumber to your favorite number. Make sure it's data type is a number.
- Log to the console favoriteNumber.

- Declare a variable called person
- Initialize person to an object with the following properties
  - firstName
  - lastName
  - age

log to the console person.

Here's an example of a variable called user set to the following properties

- email
- username

```js
let user = {
  email: "John123@gmail.com",
  username: "john123",
};
```

## Exercise 7

In the class-10 folder, create a folder called exercise-7.

Declare a variable called a and set it equal to 5.
Declare a variable called b and set it equal to 10.

Use a and b to demonstrate javaScript operators.

Here is the plus operator demonstration.

```js
console.log("a + b is ", a + b); // a + b is 15
```

Log the evaluation of a and b using the following [operators](https://www.w3schools.com/js/js_operators.asp)

- Multiplication
- subtraction
- division
- Modulus
- Exponentiation
- Division
- Increment
- decrement

## Exercise 8

In the class-10 folder, create a folder called exercise-8.

Declare a variable called a and set it equal to 5.
Declare a variable called b and set it equal to 5.

Use a and b to demonstrate javaScript operators.

Here is the equal to sign demonstration.

```js
console.log("a == b is ", a == b); // a == b is true
```

Log the evaluation of a and b using the following [JavaScript Comparison Operators](https://www.w3schools.com/js/js_operators.asp)

- equal value and equal type
- not equal value or not equal type
- greater than sign
- less than
- greater than or equal to
- less than or equal to

## Exercise 9

In the class-10 folder, create a folder called exercise-9.

Declare a variable called firstName and set it equal to "John".

Use [Conditional Statements](https://www.w3schools.com/js/js_if_else.asp) to do the following:

If firstName is equal to John, log to the console "Found John!" otherwise log to the console "Have you found John?".

## Exercise 10

In the class-10 folder, create a folder called exercise-10.

Use a [loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration) to print numbers 0 - 50.

## Exercise 11

In the class-10 folder, create a folder called exercise-11.

- Use a built in array method like [filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) to filter out numbers less than 10 in the following array:

```js
let numbers = [1, 5, 10, 15, 20];
```

## Exercise 12

In the class-10 folder, create a folder called exercise-12.

Give an example of a [if, else if and else](https://www.w3schools.com/js/js_if_else.asp) statement.

## Exercise 13

In the class-10 folder, create a folder called exercise-13.

Use JavaScript to [change the background color](https://www.w3schools.com/jsref/prop_style_backgroundcolor.asp) of a webpage to 'green'.

## Exercise 14

In the class-10 folder, create a folder called exercise-14.

Use JavaScript to [create an h1 element](https://www.w3schools.com/jsref/met_document_createelement.asp) with content 'John's Blog Website!'.

## Exercise 15

In the class-10 folder, create a folder called exercise-15.

Given the array of numbers:

```js
let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
```

Define a function called addNumbersToWebpage.

This function needs to append a paragraph element onto to the webpage for each value of the array.

## Exercise 16

In the class-10 folder, create a folder called exercise-16.

- Define a function called add.
- This function has two parameters: a and b like so:

```js
function add(a, b) {}
```

- This function's purpose is to `return` the addition of two numbers.

- Define a function called log.
- This function has one parameter called value.
- Call this function and pass in add(10,10) as an argument.
- You should see 20 in the console.

## Exercise 16

In the class-10 folder, create a folder called exercise-16

Given the object:

```js
  let school = {
    students: 500,
    classrooms: 60,
    teachers 50
  }
```

Log to the properties of school (students, classrooms and teachers).

Here's an example.

```js
console.log(school.students);
```

## Exercise 17

In the class-10 folder, create a folder called exercise-17.

Given the array:

```js
let users = [
  {
    name: "John",
    age: 30,
  },
  {
    name: "Jimmy",
    age: 20,
  },
  {
    name: "Amy",
    age: 43,
  },
];
```

Print the content of each object that exists in the users array onto the webpage except the object that has the name `Jimmy`.

## Exercise 18

In the class-10 folder, create a folder called exercise-18.

- Use an [event listener](https://www.w3schools.com/jsref/event_onclick.asp) to listen for a button click. When the user clicks on this button, log to the console "Clicked!".

## Exercise 19

In the class-10 folder, create a folder called exercise-19.

- Create a h1 element in your html file with content "Click me to change the color of this text!"
- Use an event listener to do just this but instead of adding the event listener in html use [addeventlistener](https://www.w3schools.com/js/js_htmldom_eventlistener.asp)

## Exercise 20

In the class-10 folder, create a folder called exercise-20.

Use [setinterval](https://www.w3schools.com/jsref/met_win_setinterval.asp) to append a div to the webpage every 1 second. This div should a 200px by 200px red square.

## Exercise 21

In the class-10 folder, create a folder called exercise-21.
Create a nested loop that will the contents of an array twice.

For example, here I am printing each number 5 times each.

```js
let numbers = [1, 2, 3];
for (let i = 0; i < numbers.length; i++) {
  for (let j = 0; j < 5; j++) {
    console.log(numbers[i]);
  }
}
```

## Exercise 22

In class-10, create a folder called exercise 22.

Given the string

```js 
  let str = "'Here's Johnny!' is a famous movie line from..." 
```

Define a function called capitalizeEachWord with one parameter. This function will capitalize each word. 

```js 
  let str = "'Here's Johnny!' is a famous movie line from..." 
  function capitalizeEachWord(sentence){
    // Build your logic here
  }

  capitalizeEachWord(str); // 'Here's Johnny!' Is A Famous Movie Line From... 
```


## Exercise 23

In class-10, create a folder called exercise 23.

Given the string

```js 
  let str = "I am 10. My address is 1112 Some Str." 
```

Define a function called countNumbersInSentence with one parameter. This function will return the count of total numbers

```js 
  let str = "I am 10. There are 14, 24 or maybe only 10 water bottles left in the house." 
  function countNumbersInSentence(sentence){
    // Build your logic here
  }

  countNumbersInSentence(str); // 4
```


## Exercise 24

In class-10, create a folder called exercise 24.

Given the string

```js 
  let num = 1010101
```

Define a function called countZeros with one parameter. This function will return the total number of 0s.

```js 
  let num = 1010101
  function countZeros(num){
    // Build your logic here
  }

  countZeros(str); // 3
```


## Exercise 25

In class-10, create a folder called exercise 25.

Given the string

```js 
  let name = "Amy"
```

Define a function called updateNames with one parameter. This function will replace the name John withe given parameter.

```js 
  function updateNames(name){
  let sentence = "Hello, my name is John. My friend's name is also John."
    // Build your logic here
  }

  updateNames(name); // "Hello, my name is Amy. My friend's name is also Amy."
```

