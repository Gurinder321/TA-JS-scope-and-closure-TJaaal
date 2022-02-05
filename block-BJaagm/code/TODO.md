1. What does thread of execution means in JavaScript?

It goes through our code, line by line.

2. Where the JavaScript code gets executed?

Whenever the the program runs, an execution context is created. In this phase javascript alllocated the memory to all the vairabl and function present in the program.

3. What does context means in Global Execution Context?

It's the arguments created in the execution phase

4. When do you create a global execution context.

Only get created once when JavaScript engine is running your code

5. Execution context consists of what all things?

Call stack and a memory heap

6. What are the different types of execution context?

The creation phase and execution phase

7. When global and function execution context gets created?

As soon as the program runs

8. Function execution gets created during function execution or while declaring a function.

Function execution

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

```js
var user = "Arya";

function sayHello() {
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-1.png)

```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount) {
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-2.png)

```js
var age = 21;

function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  } else {
    return `You are a kid`;
  }
}

var whoAmI = customerMessage(age);
var whoAmIAgain = customerMessage(12);
```

<!-- Put your image here -->

![](./img/image-3.png)
