Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(username); // output
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

First the code will go through declaration and function phase, Storing them into memory.
Second step is to go through the execution phase. It'll try to look for username but unable to find it because to look for variables, you can only bubble out. Not bubble in

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); // output
```
The console will print out "Arya" because the brackets are ignored

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output
```
Code goes into creation phase. Username is undefined
Execution phase: The machine is reading username
It reads the if statement -> it's true
the console prints out username: "Arya"

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(username); // output
```

Code goes into creation phase. Username is undefined
Execution phase: The machine is reading username
It reads the if statement -> it's true
the console prints out username: "Arya"


5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(username); // output
```

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output
```

1. Creation phase - Username is undefined
Execution phase - username is "John"
Still in execution phase - Go over the if statement
When it discovers username if defined again. It gives us an error.
Uncaught SyntaxError: Identifier 'username' has already been declared


7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(username); // output
```

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // output
}
console.log(i, 'Second'); // output
```
1. Creation phase. i is undefined
2. Execution phase
  declare variable = 0
  continue to run the block statement
  1, 2, 3, 4, 5, 6, 7, 8, 9
3. Console.log the "second" as a 10

  


9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // output
}
console.log(i, 'Second'); // output
```
Same thing will happen as question 8. 
However, you'll get a ReferenceError for line 4 because i is not defined.