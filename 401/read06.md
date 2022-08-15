# **Authentication**

> ## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.

- Hashing is an algorithm that a program generates to store your password. Making it secret.

2. What is Bcrypt?

- BCrypt is an algorithm that slows down a brute attack by using a technique called `key stretching`.

3. Why might you use something like Bcrypt?

- The faster the attack the slower the algorithm making it much more difficult for someone to access your password.

> ## Basic Auth

1. What is Basic Authentication?

- basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

2. What properties are necessary in the header of a Basic Auth request?

- `HTTP`

3. How are `username:password` in Basic Auth encoded?

- They are encoded with `Base64` in transit and not encrypted or hashed in any way.

> ## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.

- A verification process that checks that the user/website/entity is who they say they are.

2. How should your error messaging respond (both HTTP and HTML)? Why?

- with `Status 500` becasue its a server error. Too much info on the error may give away crucial information to a potential hacker.


### Recources:

- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)


## Things I want to know more about