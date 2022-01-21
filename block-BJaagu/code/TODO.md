Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT
var numA = 21,
  numB = 30;
```

NaN - because numB hasn't been declared

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT
let numA = 21,
  numB = 30;
```

ReferenceError. numA hasn't been defined

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //OUTPUT
```

51
How??

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

First console log will be undefined
???

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT
function sayHello() {
  console.log(username);
}
```

Make sense. Username gets stored at "tyrion" 2. function gets executed 3. The function runs are the block code get executed

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT
let sayHello = () => {
  console.log(username);
};
```

ReferenceError: username in not defined.
The sayHello() function runs and executed the the code block and username has been defined

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

sayHello is not defined

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```
sayHello is not defined

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // OUTPUT
let sayHello = () => {
  console.log(username);
};
```
sayHello is not defined

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // OUTPUT
```
undefined

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // OUTPUT
```

John

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // OUTPUT
```
ReferenceError: Cannot access 'username' before initialization