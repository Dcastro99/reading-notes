# **Redux - Additional Topics**

> ## Redux Toolkit (RTK)

1. What concerns are addressed by Redux Toolkit?

- "Configuring a Redux store is too complicated"

- "I have to add a lot of packages to get Redux to do anything useful"

  - "Redux requires too much boilerplate code"

2. What does configureStore() do?

- automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

3. How would I use createSlice()?

- You can create a slice and it automatically generates a reducer which you can use in your compnents that need to have the state information

> ## MobX

1. What is Mobx?

- State management tool

2. How does MobX make it “impossible” to produce an 3. inconsistent state?

- They make sure that everything that can be derived from the application state, will be derived. Automatically.

3. How would we build a reactive user interface?

- The `observer` HoC wrapper from the `mobx-react-lite` package fixes that by basically wrapping the React component in `autorun`. This keeps the component in sync with the state.

> ## Tutorial

1. What take-away(s) did this tutorial provide?

- Relativley easy to understand and not to complicated to implemet

### recources

- [Redux](https://redux-toolkit.js.org/introduction/getting-started)

- [Mobx](https://mobx.js.org/getting-started.html)
