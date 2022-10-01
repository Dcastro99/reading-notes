# **Component Based UI**

> ## react hello world

1. What are the building blocks of a React app?

- elements and components.

2. What is the difference between an element and a React component?

- elements are what help display what the page renders and components handle the functions in the code.

3. What are some advantages of React’s component based architecture?

- props are read only

> ## introducing JSX

1. What is JSX and why do we use it?

- It's a syntax extension to JavaScript. We use it with React to describe what the UI should look like.

2. Describe the process of embedding JavaScript expressions in JSX.

- Well we are able to pass infomation to a funtion and return that information back with the ability to access it.

to embed the information we'd wrap the information in an element link `<h1>{information} </h1>` or `<footer> {information}<footer>`.

3. Is it safe to embed user input in JSX? Explain.

- yes, By default, React DOM `escapes` any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that’s not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS `(cross-site-scripting)` attacks.

> ## rendering elements

1. Explain what a React Component is to a non-technical friend.

- Components are basically seperat funtions that pass information between each other. Each compenet are isolated and take inputs and return it letting the web page know how it should be displayed.

2. Describe mutability and React Components, specifically, how is the UI updated?

- well and example would be information given by the user. Lets say the user name is null or undefined. Once the user inputs his informating, the state of that changes to the users name therfore now the `<h1>{username}</h1>` will diplay on the screen.

3. If changes are made to the UI, what does React update?

### Resources

- [JSX](https://reactjs.org/docs/introducing-jsx.html)
