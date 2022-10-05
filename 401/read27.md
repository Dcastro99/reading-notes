# **`useState()` Hook**

> ## Introducing Hooks

1. What was the motivation for introducing Hooks?

- Hooks solve a wide variety of seemingly unconnected problems in React.

2. What changes are important regarding implementing Hooks versus Component Classes?

- Hooks don't contain any breaking changes.

3. Hooks allow you to reuse stateful logic without changing ( your component hierarchy ).

> ## hooks api

1. Name two rules imposed by React Hook usage.

- Only call hooks from the top level and only call hook sin React fuctions. It won't work in regular javascript.

2. How would you identify a custom Hook and why might you create one?

- Creating a custom hook allows you to call other hooks. You might want to create one if you have some special function you'fdlike to implement.

> ## the state hook

1. What is a Hook?

- A Hook is a special function that lets you “hook into” React features.

2. When would I use the `useState` Hook?

- If you write a function component and realize you need to add some state to it.

3. If you were to add React state to a function component by declaring a state variable:
4. What does calling `useState` do?

- it changes state at that moment.

5. What do we pass to `useState` as an argument?

- the initial state. Could be a number or string.

6. What does `useState` return?

- the current state and a function that updates it.

> ### References

- [intro](https://reactjs.org/docs/hooks-intro.html#motivation)
- [Hooks api](https://reactjs.org/docs/hooks-overview.html)
- [State Hook](https://reactjs.org/docs/hooks-state.html)
