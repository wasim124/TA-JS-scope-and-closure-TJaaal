1. What does thread of execution means in JavaScript?

```js
ans- It goes through code line by line
```

2. Where the JavaScript code gets executed?

```js
ans- console in the browser and any server have javascript engine.
```

3. What does context means in Global Execution Context?

```js
Ans- its is default execution contex in javascript and its create only ones
```

4. When do you create a global execution context.

```js
ans- Whenever the JavaScript engine receives a script file
```

5. Execution context consists of what all things?

```js
ans - memory and code component
```

6. What are the different types of execution context?

```js
ans-Global Execution Context/GEC
    Functional Execution Context/FEC
```

7. When global and function execution context gets created?

```js
ans-The Global Execution Context gets created when we load the JavaScript file.
    Whenever a function is called, the JavaScript engine creates a different type of Execution Context known as a Function Execution Context (FEC) within the GEC to evaluate and execute the code within that function.
```

8. Function execution gets created during function execution or while declaring a function.

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

```js
var user = "Arya";

function sayHello() {
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/Hello-arya.jpg)

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

![](./img/image-name.jpg)

```js
var age = 21;

function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  } else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)
