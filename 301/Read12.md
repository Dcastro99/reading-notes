# **CRUD**

> ## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

- 100’s = the header part recieved and the server will try to comply with request.
- 200’s = request accepted
- 300’s = source no lonhger available
- 400’s = client error. invalid request
- 500’s = server errors

2. What is a status code 202? 

- request valid and accepted

3. What is a status code 308? 

- tells the client tu use another URL

4. What code would you use if an update didn’t return data to a client?

- 204

5. What code would you use if a resource used to exist but no longer does?

- 410

6. What is the ‘Forbidden’ status code?

- 403


> ## Build A REST API With Node.js, Express, & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- we want to create a veriable that links it to the .env file so the client doesnt have access to it.

2. What is middleware?

- lets us route information

3. What does `app.use(express.json())` do?

- lets the server accept JSON

4. What does the `/:id` mean in a route?

- its a parameter that is accessable by usung req.params.id

5. What is the difference between `PUT` and `PATCH`?

- patch only updates with what the client gives us. Put will update all the information at once

6. How do you make a default value in a schema?

```js

nameDate: {
  type: Date,
  required: true
  default: Date.now
}
```

7. What does a `500` error status code mean?

- server error

8. What is the difference between a status `200` and a status `201`?

- 200 = everything was successful, 201 = successfully created an object

## Things I want to know more about