# **Advanced State with Reducers**

> ## useReducer hook

1. Name an alternative to the `useState` Hook.

- `useReduce`

2. Why might the `useReducer` Hook be preferable to the `useState` Hook?

- When you have complex state logic that invloves multiple sub-values or when the next state depeneds on the previous one.

3. What are two ways to set the initial state?

One way is =

```javascript
const [state, dispatch] = useReducer(reducer, { count: initialCount });
```

Another way is =

```javascript
function init(initialCount) {
  return { count: initialCount };
}
```

> ## Ultimate Guide to useReducer

1. In terms of state, what does `useReducer` expect to receive as a parameter?

- It takes reducer as its firs parameter and the initial state as a second.

2. What does `useReducer` return?

- returns an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it.

3. Explain `dispatch` to a non-technical recruiter.

- Dispatch simply allows you to invoke an action later on in your code. If you are updating state, it'll be invoked usinf `dispatch`.
