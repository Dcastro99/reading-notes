# **Redux - Asynchronous Actions**

> ## async actions

1. Why use Redux middleware?

- benefit of using middleware like Redux Thunk or Redux Promise is that components aren’t aware of how action creators are implemented, and whether they care about Redux state, whether they are synchronous or asynchronous, and whether or not they call other action creators. The downside is a little bit of indirection, but we believe it’s worth it in real applications.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

- we deposit monet with an event handler, that is dispatched to a middleware, which then sends a request to and api. The api, the api sends a response with a payload and thats dispatched to a reducers which in turns sets it to state.

3. How are we accommodating async in our Redux app?

- We use Redux middleware to make async calls that interact with the store by dispatching actions.

> ## thunk middleware

1. Why would you need redux-thunk middleware?

- Thunks are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.

2. Redux Thunk middleware allows you to write action creators that return a _function_ instead of an action.

3. Describe how any return value from the inner thunk function will be made available.

- It will be the return value of the dispatch itself.

## Reflection

_What are your learning goals after reading and reviewing the class README?_

- Watch more tutorials on youtube on the subject.

### recources

- [redux middleware](https://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34599594#34599594)

- [Thunk middleware](https://github.com/reduxjs/redux-thunk/blob/master/README.md)
