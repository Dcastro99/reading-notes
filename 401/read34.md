# **API Integration**

> ## Review API Server Build

1. Explain the different between a query string parameter and a path parameter.

- A string parameter is simply allowing the route search for any given string provided. The path parameter is the endpiont toed to the server that will call the function from a database.

2. What would our API URL with a path id parameter be given the following information:

   1. Domain: `http://our-site.com`

   2. `v3`

   3. model name: `stuff`

   4. id: `things`

   - ( http://our-site.com/API/v3/stuff/things )

3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

Dynamic meaning it reacts/changes depending on the users choice of functionality. for example, someone entering a form with personal info is dynamic in the way it updates or creates and sends information to the api.

> ## Review Auth Server Build

1. Describe how you would use middleware to implement basic and bearer auth.

- having a users information like username and password get hashed and encrypted with bcrypt then having that funcntion passed in the enpoint of `post` when the user send given info to our server is how I would handle that.

2. Describe the handshake necessary to implement OAuth.

- When a user logs in they get routed to OAuth or Auth0. These 3rd party applications will verify the user for use and create a token that we then can use as righ of pasage.

3. Describe how Role Based Access Control works to a non-technical friend.

- In most company/ corporation there are roles like user, admin, manager, editor, etc. These rolse will have access to different funtionality within the companies computer system.
