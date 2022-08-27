1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

let percentage = (markx, total) => {
  return (marks * 100) / total;
};
```

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

````js
Ans. In javascript function can use as object and its not need to define function name.

     let fullName = (firstName, lastname) => {
      return `${firstName} ${lastName}`;
     }

4. Why is a function call an expression in JavaScript?


5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer
five = add; // Answer valid
five = five(10, 11); // Answer 21 valid
five = function () {
  return "Hello";
}; // Answer
````

6. What is the difference between function definition and function call? Explain with an example.
```js
ans-Function is a part of program defined seperately outside the program whereas function call is calling of the function.
```

7. What is the similarities between function definition and function call?
```js
ans- name of function
```

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; //valid
```

9. What is higher order function explain with an example.
```js
ans- A function that accepts functions as parameters and/or returns a function.
```

10. Explain what is callback function. Why you can pass a function inside a function?
```js
ans- a function that pass a argument to another function is called callback function.  Making functions more dynamic thats why we pass function inside function.
