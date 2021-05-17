1. What does thread of execution means in JavaScript?

execution of running multiple tasks or programs at the same time. Each unit capable of executing code is called a thread. ... However, modern JavaScript offers ways to create additional threads, each executing independently while possibly communicating between one another .


2. Where the JavaScript code gets executed?

javascript engine creates Global execution context . Context is environment where code get executes.

3. What does context means in Global Execution Context?
Context is environment where code get executes.


4. When do you create a global execution context.

Gloval execution context created by Javascript , when javascript engine run the code for first time.

5. Execution context consists of what all things?

Execution consist of memory and place where all execution will happen .

6. What are the different types of execution context?

Global execution context  and Function execution context .

7. When global and function execution context gets created?

when code run for first time then GEC created  . When you call function then FEC created .
8. Function execution gets created during function execution or while declaring a function.
function execution .


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)






```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)