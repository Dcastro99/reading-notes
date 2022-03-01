# **Debugging**

> ## Ch. 10 - “Error Handling & Debugging”

- Order of excicuting: not always does the oder of function mean that they will run in that particular order.

- a function may be waiting on another function in order to exicute.

- an example that Jn Duckett gives us is shown below:

```js

function greetUser(){
  return 'Hello ' + getName();
}

function getName(){
  let  name = 'Molly';
  return name;
}

let greeting = greetUser();
alert(greeting);
```

As you notice one funtion must wait on another in order to fully exicute.

>Object Errors
  
- EvalError - eval() function used incorrectly

- URIError - encodeURI() decodeURI(). and similar methods used incorrectly

- RangeError - Numbers not in acceptable range

- TypeError - AN unexpected data type that cannot be coerced

- ReferenceError - Tried to reference a variable that is not
  declared/ within scope

- Syntax Error - Syntax has not been followed

- Error - Generic error - the other errors are all based upon this 
  error
```html
<p>~Example from Jon Duckett~</p> ^
```
