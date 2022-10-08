# **Component Lifecycle / `useEffect` Hook**

> ## effects hook

1. What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?

-

2. When using the useEffect Hook:

   1. **What does useEffect do?**

   - The Effect Hook lets you perform side effects in function components

   2. **Why is useEffect called inside a component?**

   - Placing `useEffect` inside the component lets you access the state variable (or any props) right from the effect.

3. Explain the importance of properly implementing effects with Cleanup

- The `useEffect` Hook is built in a way that we can return a function inside it and this return function is where the cleanup happens. The cleanup function prevents memory leaks and removes some unnecessary and unwanted behaviors.

### References

- [effects hook](https://reactjs.org/docs/hooks-effect.html)

- [effects-cleanUp](https://codedamn.com/news/reactjs/useeffect-cleanup)

## Things I want to know more about
