# **Redux - Combined Reducers**

> ## Multiple Reducers Example

1. Why create multiple reducers?

- having multiple reducers allows us to maintain them a lot easier.

2. How would you combine multiple reducers?

- You combine them by usinf combinereducers() from 'Redux'

3. How will you manage state as an immutable object? why?

- You can deconstruct the state before initializing the change. (...state, change=> here)

> ## Redux Docs: Using Combined Reducers

1. `combineReducers` is a utility function to simplify the most common use case when writing _REDUX REDUCERS_ .

2. Explain how `combineReducers` assembles the new state tree.

- combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed. So, in that sense, using combineReducers does "call all reducers", or at least all of the slice reducers it is wrapping

3. How would you define initial state in an app using `combineReducers`?

- First, the createStore function can take preloadedState as its second argument. This is primarily intended for initializing the store with state that was previously persisted elsewhere, such as the browser's localStorage.

> ## Redux Docs: Combined Reducer Syntax

1. Why will you want to split your reducing functions as your app becomes more complex?

- This will allow you to manage the independant parts of state

2. The _combinedReducers_ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to _creatStore_.

3. What is a popular convention when naming reducers?

- name reducers after the state slices they manage

### RECOURCES

[combineREducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
