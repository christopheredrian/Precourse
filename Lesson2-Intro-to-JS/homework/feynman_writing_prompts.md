# Feynman Writing Prompts

## Variables
In analogy, a variable is like a basket where you can put anything that fits in it. After putting something in the basket you then give it a name. For instance I have a basket in my home, I call it "myFruits" and inside that basket I put all of my fruits in the house.

In this case the name of the basket is denoted as

` let myFruits; `

and what represents me putting all of my fruits can be something like:

// For simplicity we'll just use a string here
`myFruits = 'apple,orange,mangoes';`

So essentially variables are placeholders for something, and technically speaking variables are placeholders in the computers' memory.

As noted above variables are placeholders, and some of the things that variables can hold are: strings, integers, floating point numbers, arrays, objects, etc.

## Strings

As noted above there are numerous types that a variable can hold and one of those "data types" is string.
A string is essentially a collection of characters (number, letter, and symbols), and is denoted by placing the set of characters in a "" or a ''. For instance:

`'Christopher'` is an example of a string.
It is also equivalent to "Christopher"  

## Functions (arguments, return)

In programming, most of the time you use a set of codes repeatedly, to prevent the repeated lines of code we can package these into what we call functions. A function is like a cookbook, it contains steps needed to be done (in this case code) in order for the function to complete.

There are two optional things that we can pass (input) and return (output) from a function, these are called the arguments and the return declaration respectively.

For instance, we can create a function of adding two integers and returning that to the program who called the function.

```javascript
// a and b are the arguments - its what gets passed into a function
function add(a, b){
	let sum = a + b;
	// we return the sum to the one who called (invoked the function)
	return sum; 
}
```

// We invoke the function and pass the two arguments
let theSumOfTwoAndThree = add(2,3); // theSumOfTwoAndThree will contain the integer 5


## If Statements

If statements are conditions which will decide what path of the program will take before continuing the execution. The if statement typically will check if a condition is true or false.
For instance lets say If I am hungry (true), I will eat. Denoting this in code will look something like:

```javascript
if(true){
	// This code will execute.
	console.log("I will eat");
}
```

## Boolean values (true, false)

In discussing the if statement above, it is important to understand boolean values. Boolean values can either be true or false, and these boolean values can be assigned to variables as such:

`let iamHungry = true;`

and combining it with the code from the if statement above

```javascript
let iamHungry = true;
if(iamHungry){
	// This code will execute.
	// since iamHungry is true
	console.log("I will eat");
}

```
