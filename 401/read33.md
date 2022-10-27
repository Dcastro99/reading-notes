# **`<Login />` and `<Auth />`**

> ## What is Role Based Access Control (RBAC)?

1. What is Role Based Access Control (RBAC)?

- Basically its a way to setup an netwrok based on a person's role.

2. Share some an example of RBAC including all possible CRUD operations and correlating roles.

```javascript
{
role: Admin(create,read,update delete)
role: Editor(create,read,update delete)
role: user(read,update)
}

```

3. What are the Benefits of RBAC?

- reducing administrative work, maximizing operational efficiency and improving compliance.

> ## _react-cookie library_ & _react-cookies component_

1. Describe some react-cookie features.

- You are able to set the cookie name and then use it in other components using `withCookies` as a state feature.

2. Describe some react-cookies features.

- you can use `.load(name, [doNotParse])` to a cookie value.

3. Which library would you prefer would you prefer? Why?

- I would have to play in the sandbox with both of them to really have a better understanding but from the get go, I'd choose react-cookie. Seems easier to work with.
