# TypeScript Exercises

**Read before starting**
In Code-Labs, create a new folder called class-12. You will be working in the class-13 folder for today.

In class-13 run `npx tsc --init`. This will configure your TypeScript environment and prevent unusual errors.

To transpile a typescript file into js, run ths command in the terminal

```
npx tsc file-name.ts
```

## Exercise 1:

Create a folder called exercise-1. Create a file called index.ts.

Define a class a called user.

User should have properties, name of type string, age of type number and of height string.

Create a variable called person that is of type User.

Set this user to a user instance and fill each property this user has with the following

- Name should be Amy
- Age should be 25
- height should be 5'6.

**Here's an example**

```js
let person = new User();
person.name = "John";
person.age = 12;
perosn.height = "5'6";
```

Be sure to transpile your ts file to js.

## Exercise 2:

Create a folder called exercise-2. Create a file called index.ts.
Define a class called Logger.
Logger has a series of methods such as:

- logRandomNumber() - log a random number between 0 to 1000
- logARandomColor() - given an array of colors, output a random color to the console.
- logTo100() - output to the console numbers 0 to 100

Create a logger instance to execute these methods.

## Exercise 3

Create a folder called exercise-3. Create a file called index.ts.
Create a class called User. This class has a property called favoriteColor of type string.

Create a variable that is of type user and set that to a new user instance.
Assign this variable's favoriteColor property to 'Blue'. 

Define a method inside of the User class called LogFavoriteColor. 

The purpose of this method is to log the user instances favorite color. Do not manually log 'Blue'. Be sure to access the user instance's favoriteColor property using the 'this' keyword.

Use this [resource](https://www.w3schools.com/js/js_classes.asp) as a demonstration.

