For the given code below:

- re-write the code in ways that system will understand

For Example:

1.

```js
var username = "Arya";
let brothers = ["John", "Ryan", "Bran"];

console.log(username, brothers[0]);

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello("Test");
```

<!-- Answer -->

var username = undefined;
let brothers;

let message;
var nextMessage = undefined;

function sayHello(name) {
return `Hello ${name}`;
}

username = 'Arya';
brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

message = sayHello(username);
nextMessage = sayHello('Test');

````

```js
// Declaration Phase
var username = undefined;
let brothers;

function sayHello(name) {
  return `Hello ${name}`;
}

let message;
var nextMessage = undefined;

// Execution Phase

username = 'Arya';
brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

message = sayHello(username);
nextMessage = sayHello('Test');
````

2.

```js
console.log(username, numbers);

var username = "Arya";
let number = 21;

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello("Test");
```

<!-- Answer -->

Declaration Phase:

var username = undefined;
let number;

function sayHello(name) {
return `Hello ${name}`;
}

let message;
var nextMessage = undefined;

Execution Phase:

console.log(username, numbers);
username = 'Arya';
number = 21;

message = sayHello(username);
nextMessage = sayHello('Test');

```js
// Your code goes here
```

3.

```js
console.log(username, numbers);
let username = "Arya";
let number = 21;

let sayHello = function (name) {
  return `Hello ${name}`;
};

let message = sayHello(username);
var nextMessage = sayHello("Test");
```

<!-- Answer -->

```js
// Your code goes here
```

4.

```js
let username = "Arya";
console.log(username, numbers);

let number = 21;
let message = sayHello(username);

let sayHello = function (name) {
  return `Hello ${name}`;
};

var nextMessage = sayHello("Test");
```

<!-- Answer -->

```js
// Your code goes here
```

Declaration Phase:
let username;

let number;
let message;

let sayHello

var nextMessage = undefined;

Execution Phase:
username = 'Arya';
console.log(username, numbers);

number = 21
message = sayHello(username);

sayHello = function (name) {
return `Hello ${name}`;
};

nextMessage = sayHello('Test');

5.

```js
var name = undefined;
let age;
console.log(name);
console.log(age);
name = "Lydia";
age = 21;
```

<!-- Answer -->

Won't work

```js
// Your code goes here
```

6.

```js
function sayHi(name) {
  var name = undefined;
  let age;
  console.log(name);
  console.log(age);
  name = "Lydia";
  age = 21;
}

sayHi();
```

Undefined

<!-- Answer -->

```js
// Your code goes here
```

7.

```js
function sayHi(name) {
  var name = undefined;
  let age;
  console.log(name);
  console.log(age);
  name = "Lydia";
  age = 21;
}
sayHi();
```

<!-- Answer -->

Undefined
Cannot access 'age' before initialization

```js
// Your code goes here
```

8.

```js
let sayHi;
sayHi();
sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = "Lydia";
  let age = 21;
};
```

sayHi is not defined

<!-- Answer -->

```js
// Your code goes here
```

9.

```js
let num1;
var sum = undefined;
let num2;
num1 = 21;
console.log(sum);
sum = num1 + num2;
num2 = 30;
```

<!-- Answer -->

undefined
num2 is not defined

```js
// Your code goes here
```

10.

```js
var num1 = undefined;
let sum2;
num1 = 21;
let add;
let num2;
let sum;
function addAgian(a, b) {
  return a + b;
}

sum2 = addAgain(num1, num2, 4, 5, 6);
add = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
num2 = 200;

sum = add(num1, num2, 4, 5, 6);
```

<!-- Answer -->

Declaration Phase:
var num1 = undefined;

let sum2 = undefined;

let add;

function addAgian(a, b) {
return a + b;
}
let num2;

let sum;

Execution Phase:
num1 = 21;

sum2 = addAgain(num1, num2, 4, 5, 6);

add = (a, b, c, d, e) => {
return a + b + c + d + e;
};

num2 = 200;

sum = add(num1, num2, 4, 5, 6);

```js
// Your code goes here
```

11.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

let add = (a, b) => {
  return a + b;
};
```

<!-- Answer -->

Declaration Phase:
function test(a) {
let num1 = 21;
return add(a, num1);
}

let sum = test(100);

let add = (a, b) => {
return a + b;
};
Execution Phase:

```js
// Your code goes here
```

12.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}
let sum;

function add(a, b) {
  return a + b;
}
sum = test(100);
```

<!-- Answer -->

```js
// Your code goes here
```
