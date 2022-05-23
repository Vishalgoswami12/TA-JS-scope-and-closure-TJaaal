1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```
let percentage=function percentage(marks, total) {
  return (marks * 100) / total;
}

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```
Function Decleration

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
function Expression
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
Function Expression
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
Function Expression
```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

To store a function in a variable is known as function expression

let addNumber=function add (numA,numB){
  return numA+numB;
}

4. Why is a function call an expression in JavaScript?

Because function call an expression call the function with function name operator().

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer Valid 
five = add; // Answer Valid
five = five(10, 11); // Answer valid
five = function () {
  return 'Hello';
}; // Answer valid
```

6. What is the difference between function definition and function call? Explain with an example.

function defnition is a step to define afunction and function call is call by ().
function defnition

function multiply(numA,numB){
  return numA*numB
}
function call

multiply(6,5)

7. What is the similarities between function definition and function call?

There is no simlarities between function defnition and function call.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid
Valid
```

9. What is higher order function explain with an example.

 A “higher-order function” is a function that accepts functions as parameters and/or returns another function in it.
 function add(a,b){
   return function(){
     return a+b
   }
 }

10. Explain what is callback function. Why you can pass a function inside a function?

A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.

function greeting(name) {
  alert('Hello ' + name);
}

function processUserInput(callback) {
  var name = prompt('Please enter your name.');
  callback(name);
}

processUserInput(greeting);
