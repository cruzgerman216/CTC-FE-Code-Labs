# TypeScript Exercises

**Read before starting**
In Code-Labs, create a new folder called class-12. You will be working in the class-12 folder for today.

In class-12 run `npx tsc --init`. This will configure your TypeScript environment and prevent unusual errors.

To transpile a typescript file into js, run ths command in the terminal

```
npx tsc file-name.ts
```

## Exercise 1:
Create a folder called exercise-1. Create a file called index.ts. We won't need the browser(html) to execute this.
Declare a variable called phoneNumber that is of type string. Set it to "123-456-7890".
Log to the console phoneNumber.
<br>

**Let's transpile this file into JavaScript.**
<br>

To transpile index.ts into JavaScript, be sure to open your terminal and that you are in the exercise-1 folder. If not be sure to use the 'cd' command to navigate into a folder and '..cd' to navigate to the parent folder.
<br>

Once in the correct folder. Run `tsc index.ts`. This should create a `index.js` file. 
<br>
Then run `node index.js`. This file should print phoneNumber.

## Exercise 2:
Create a folder called exercise-2 and file called index.ts.
Create a variable called "myDogsName" that is of type string in TypeScript. Set it to a name. 
Log to the console myDogsName.

Transpile this into JavaScript.

## Exercise 3: 
Create a folder called exercise-3 and file called index.ts. 
Create a variable called post that is of type object with properties title and description. Each property is a string. Assign post to a value. 
Log to the console post.

Transpile this into JavaSCript.

## Exercise 4:
Create a folder called exercise-4 and file called index.ts. 

Define a function called `add`. This function will have two parameters: a and b that are both numbers. Provide type checking for these parameters and build out the logic to the function. The end result should evaluate a plus b. 

## Exercise 5: 
Create a folder called exercise-5 and file called index.ts. 

Define a function called formASentence. Log to the console "Hello! My name is 'name'. I am 'age and I am a 'occupation'.

Provide type checking for the parameters.
```ts 
function formASentence(name, age, occupation){
  // Build your logic here
}

formASentence("John", 22, "Doctor")
// Should console log "Hello! My name is John. I am 22 and I am doctor!
```


## Exercise 6: 
Create a folder called exercise-6 and file called index.ts. 

Define a function called isOdd. This function determines whether a value is odd. If the parameter is odd then return true.

Provide type checking for the parameters.
```ts 
function isOdd(num){
  // Build your logic here
}

isOdd(3) // true
isOdd(2) // true
isOdd(11) // true
```
## Exercise 7: 
Create a folder called exercise-7 and file called index.ts. 

Define a class called animal. This class should define properties: name of type string, age of type number and region of type region; 
Define a region class. This class should define properties: name of type string.

Create a region instance that has the name "Africa".
Create a animal instance that has the name "Johnny the Lion", 5 for the age and region to be set to the instance with the name "Africa".

Log these instances to the console.

Be sure to provide type checking on all properties.
