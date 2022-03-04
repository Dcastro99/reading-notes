# **State and Props**

> ## React Docs - lists and keys

1. What does .map() return?

```js
map() creates a new array from calling a function for every array element.

map() calls a function once for each element in an array.

map() does not execute the function for empty elements.

map() does not change the original array.
```

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

+ You can build collections of elements and include them in JSX using curly braces {}.

3. Each list item needs a unique ____.

+ key

4. What is the purpose of a key?

+ Keys help React identify which items have changed, are added, or are removed.

> ## The Spread Operator

1. What is the spread operator?

+ The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

2. List 4 things that the spread operator can do.

```html
1. Copying an array
2. Concatenating or combining arrays
3. Using Math functions
4. Using an array as arguments
```

3. Give an example of using the spread operator to combine two arrays.

```js
const myArray = [`1`,`2`,`3`]
const yourArray = [`4`,`5`,`6`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 1 2 3 4 5 6
```

4. Give an example of using the spread operator to add a new item to an array.

```js
const fewNum = ['1','2','3']
const fewMoreNum = ['4', '5', ...fewNum]
console.log(fewMoreNum) //  Array(5) [ "4", "5", "1", "2", "3" ]
```

5. Give an example of using the spread operator to combine two objects into one.

```js

const objectOne = {firstName: "Bob"}
const objectTwo = {lastName: "Smith"}
const objectThree = {...objectOne, ...objectTwo, saysHey: "Hey!"}
console.log(objectThree) // Object { hello: "bob", world: "Smith", laugh: "Hey!" }
const objectFour = {...objectOne, ...objectTwo, saysHey: () => {console.log("Hey!".repeat(5))}}
objectFour.saysHey() // Hey!Hey!Hey!Hey!Hey!
```

> ## How to pass functions between components

1. In the video, what is the first step that the developer does to pass functions between components?

+ Creates the function where ever the state is that he's going to change.

2. In your own words, what does the increment function do?

+ Increment is a function that allows objects to pass through and increment and update the count.

3. How can you pass a method from a parent component into a child component?

+  using this.props

4. How does the child component invoke a method that was passed to it from a parent component?

+ Same way using this.props I believe

> References:

- [w3schools](https://www.w3schools.com/jsref/jsref_map.asp)

- [react.js.org](https://reactjs.org/docs/lists-and-keys.html)

- [medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

