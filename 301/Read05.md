# **Putting it all together**

> ## Thinking in React

1. What is the single ```responsibility principle``` and how does it apply to components?

- based on the ifo provided by reactjs.org "a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents." So if a component starts growing it'll need different components to provide it information needed for the growth.

2. What does it mean to build a ‘static’ version of your application?

+ THis means to build each component and have it render on the page even if it wont work fuctionally.  Example: create a search bar and render it even though it may not actually work.

3. Once you have a static application, what do you need to add?

- basically you need fto have it work at a minimal level first after that.

4. What are the three questions you can ask to determine if something is state?

+ are the props being passed or are they being managed within the component.  is there a constructor in the constructor? are props being passed through 'super'?

5. How can you identify where state needs to live?

- depending what components need the information that state is rendering, you would put it at the highest level i order for it to cascade to the compnents that need that information or data.

> ## Higher-Order Functions

1. What is a “higher-order function”?

+ [Here](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK) it states that ***"Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions."***

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

+ looks like we set m > n in the original function. GreaterThan10 is equal to the original function passing 10 as a parameter. We then call greaterThank10 passing 11 which would be calling is greaterThan10(11) > greatherThan(10). this is results into is 11 > 10 = true.

3. Explain how either map or reduce operates, with regards to higher-order functions.

+ Well in order to get the end result of what you'd like to map() it would need to run its funtional process to give you that information to do what you need with. Thos can be considered a higher-order funtion.

## Things I want to know more about