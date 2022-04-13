# **Authentication**

> ## What is OAuth

1. What is OAuth?

- its a freamework created for servers to safely allow authentication access to their assets without actually disclosing login info.

2. Give an example of what using OAuth would look like.

- its basically another website that gives permission to the site a user is logging into and grantinf them permission

3. How does OAuth work? What are the steps that it takes to authenticate the user?

- A second website connects on the behalf of the user
- a one-time token is generated for the parties involved
- first sent to the user software
- if not authorized the client may be asked to authorize. 
- the usuer is asked to approve and then gives approval
- the user is given an approved acess token
- user gives token to the first website
- the first website gives the approved token to the second website on users behalf
- user sees successfully completed transaction


4. What is OpenID?

- as mentioned in a StackOverflow comment 
  - Oauth is for maschines accessing maschines
  - OpenId is for humans loggin into maschines

> ## Authorization and Authentication flows

- What is the difference between authorization and authentication?

- authorization grants access to a user from one computer to another and authintication grants access based on the user.

- What is Authorization Code Flow?

- the process in which authorization takes place

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

- basically its a code verifier. Another process to authenticate

- What is Implicit Flow with Form Post?

- user to accesses app, authO is accessed by app, authO asks user to login and credantia;s, user gives it back and authO gives it to ID token to app

- What is Client Credentials Flow?

- Auth0 certifies after user requests and then the user provides token to API

- What is Device Authorization Flow?

- occurs on the device requesting authorization and the other occurs in a browser.

- What is Resource Owner Password Flow?

- requests that users provide credentials (username and password), typically using an interactive form.