1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```

let percentage = function(marks, total) {
return (marks \* 100) / total
}

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```

let percentage = (marks, total) => (marks \* 100) / total

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Function expression is used when the function is stored inside a variable. It's not executed though.

4. Why is a function call an expression in JavaScript?
   A function call is an express when the specific function is provided with an argument(s)

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid
five = add; // valid
five = five(10, 11); // valid
five = function () {
  return "Hello";
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.
   A function definition is when you define a function. A function call is when you call/execute that specific function.

7. What is the similarities between function definition and function call?
   A function definition is when you define a function. A function call is when you call/execute that specific function.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; // invalid
```

9. What is higher order function explain with an example.

A function that takes a function as an argument, or returns a function

10. Explain what is callback function. Why you can pass a function inside a function?

A callback function is 1) accessible by another function, and 2) is invoked after the first function if that first function completes∆
