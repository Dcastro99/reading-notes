# **Express, NPM, TDD, CI/CD**

> ##  An introduction to Nodejs and Express

Having a better understanding of the relationship between Node.js and Express will help in the understanding the relationship between server/client relationship and build a application that utilizes this understanding.

1. Explain middleware, answer as though I were a non-technical recruiter.

- Middleware is the middleman. It recieves a request from the client and can perform different tasks like execute code or make changes to the request and respond objects or call the next middleware.

2. Express the most popular __ __ ____.

- Node web framework.

3. Express is “unopinionated.” What does that mean?

- It means it's less restricted and the developer has more control on what tools or process to use in order to exicute funtionality.

4. What is a module and why is modularity useful to us as developers?

- A module is like a component. It can help developers refactor code and simplify it.

> ## What is NPM?

1. What version of npm are you running on your machine?

- 8.11.0

2. What command would you type to install a library/package called ‘jshint’ into your node project?

 ```
npm install -g jshint
```

> ## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.

- Tests are important becasue it allows you to create a system of check and balances. If you create a test that fails if you don't meet the required funtionality, then you have the opportunityto fix the root issue in an early stage of development.

2. What are three expected benefits of testing

- many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
- the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
- although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

- Individual pitfalls 
  - Forgetting to run tests frequently
  - Writing too many tests at once
- team pitfalls
  - Partial adoption, only few developers on the team use them.
  - not used do to lack of maintenance of tests

> ## CI/CD

1. What are three benefits of Continuous Integration?

- reduce merge conflicts
- Catch bugs
- Confidence that the code is working

2. What is the difference between Continuos Delivery and Continuous Deployment?

- Difference between the two are:
  - Delivery - Develope to release anytime
  - Deployment - Deploy new features immediately

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background

- Github uses "Webhooks to send messeges to external systems about activity in the users project

Websites used:

- [On Middleware](https://selvaganesh93.medium.com/how-node-js-middleware-works-d8e02a936113)

- [On testing](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

- [video:CD/CI](https://www.youtube.com/watch?v=xSv_m3KhUO8)

 ## Things I want to know more about