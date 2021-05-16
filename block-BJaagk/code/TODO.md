1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentage = function (marks , total) {
  return (marks * 100) / total;
}

let percentage =(marks , total) => {
  return (marks * 100) / total;
}



// Your code goes here
```


2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

let percentage =(marks , total) => {
  return (marks * 100) / total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

A JavaScript function can also be defined using an expression. A function expression can be stored in a variable: var x = function (a, b) {return a * b}; After a function expression has been stored in a variable, the variable can be used as a function. ... They are always invoked (called) using the variable name.





4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer
five = add; // Answer
five = five(10, 11); // Answer
five = function () {
  return 'Hello';
}; // Answer
```

6. What is the difference between function definition and function call? Explain with an example.

function definition start with "function" keyword .   when we use  () after function name then it is function call .

     function fullName (a , b) {
      return ` {a} {b}`
}   // function definition

fullName()  // function call

7. What is the similarities between function definition and function call?



8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid
```

9. What is higher order function explain with an example.

A function that accepts and/or returns another function is called a higher-order function. It's higher-order because instead of strings, numbers, or booleans, it goes higher to operate on functions


var items = ["Apple", "Windows", "Linux", "Kindle", "Quiz"]
var charlength = items.map(function(e){
    return e.length
})

10. Explain what is callback function. Why you can pass a function inside a function?


 a callback is a function passed into another function as an argument to be executed later. To find all the odd numbers in the array, you can use the filter() method of the Array object. The filter() method creates a new array with the elements that pass the test implemented by a function..