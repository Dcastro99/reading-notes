# **In memory storage**

> ## Understanding the JavaScript Call Stack

1. What is a ‘call’?

- it invokes a function and the call stack is synchonous

2. How many ‘calls’ can happen at once?

- 1

3. What does LIFO mean?

- Last in, first out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

```js
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```
( example taken from: [here](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4))

5. What causes a Stack Overflow?

- when a function calls itself

> ## JavaScript error messages

What is a ‘refrence error’?

- an error kind of like when you haven't yet declared a veriable, an error code diplays this messege.

What is a ‘syntax error’?

- Basically when something isn't written correctly as a function

What is a ‘range error’?

- an array cannot have a negative length. errors out

What is a ‘type error’?

- when using Numbers instead of strings and returns undifined

What is a breakpoint?

- point in which your code stops

What does the word ‘debugger’ do in your code?

- debuf your code

## Things I want to know more about