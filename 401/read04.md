# **Data Modeling**

> ## nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?

- sql database

2. What type of database is the best fit for hierarchical data storage?

- non sql database

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

- sql is scalability is verticle. Basically you han ram up cpu on one server to handel the load. nosql you can throw multiple servers to the load and this is a horizontal scalabilty feature.

> ## sql modeling techniques

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

- This means that an enrty in one table may be related in a few others. We write them as many-to-one relationship.

2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

Answer: `create` // `diagrams`

3. Explain the difference between a primary and foreign key.

- Tables usially have one primary key. It identifies the table. Foreign Key is a column or set of columns that match the promary key.

> ## sql vs nosql

1. How do we treat keywords and parameters differently in SQL syntax?

- They are commands to retrieve data and updating deleting data

2. Define normalization within the context of schemas and data.

- Means how ever we bring in data or have/missing data we have to make it fit the schemas format

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

- one-to0one :

```
User has an id for a contact data. Only one user with this id
```

- one-to-many
```
User to product. One User can have many products.
```

- Many-to-many
```
User to roles. Many users can have many roles.
```

 ## Things I want to know more about