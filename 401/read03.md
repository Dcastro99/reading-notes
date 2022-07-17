# **Express REST API**

> ## ES6 Classes

1. Classes are a template for creating ____.

- objects

2. Can a class declaration be hoisted?

- yes

3. How would you describe a constructor and contextual “this” to a non-technical friend?

- `this` refers to an object or points to and object that it is bound to. If the object had a key of name and the name was Bob then `this.name` would equal to Bob.

> ## Epress Routing

1. Within Express, what does routing refer to?

- refers to how an application’s endpoints respond to client requests

2. What is the difference between a route path and a route method?

- Route methods define the endpoints with the request made. Route paths can be strings, string patterns, or regular expressions

3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?

- when you have more than one callback function.

> ## Express Routing

1. What is an Express Router?

- provides us with the routing APIs like .use, .get, .param, and route

2. By what mean do we initialize `express.Router()` in an express server?

```
const express = require('express');
const router = express.Router();
```

3. What do we use route middleware for?

- a way to do something before a request is processed

## Things I want to know more about

> references:

- [on using express](https://expressjs.com/en/guide/routing.html)

- [on express routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)
