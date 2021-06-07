1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
In first `sum` used return is a statement that allow a value back to where it was called. and 
In second `sum` used console.log is a function that inspects values for us.


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

// 
The value of `first` and `Second` will be sum of a + b if Function called.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

// output  36, 

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

// let add = function sum(a, b) {
  return a + b;
}
yes I can store by the rule of Function expression.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

// function sayHello(name){
  return `Hello Arya`
}
sayHello();

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
"Hello, John" , Concatinated
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1
    John
showMessage(); // Output 2
 "Hello, John"
alert(userName); // Output 3
John
```

8. What is a Anonymous Function give example of three functions.
If a function expression  has no name,these type of function expression 
 is known as anonymous function. exp: -

 const addNumbers = (numA,numB) => {
   return numA + NumB
 },

 let getSquare = (numA * numA) => {
   return numA * numB
 },

 const subtractNumbers = (numA - numB) => {
   return numA - numB
 }
9. Can function declaration be a Anonymous Function? Explain
Yes,Because Anonymous function is a Short form of function declaration.


10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
function sum(a, b) {
  return a + b;
},

  let userName = `Ram`
  function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
},

function sub(a, b) {
  console.log(a - b);
},

function getSquare(n){
  return n * n;
},
function addNumbers(a,b){
  return a + b;
}