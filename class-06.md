# **Problem Domain, Objects, and the DOM**

> ## Chapter 3 - Object Literals :rocket:

>> Variables and functions

- a variable in part of an object is considered a *property*
 
- a function that is part of an object is considered a *method*

>> *example*

```js
let retaurant = {
  name: 'Baracoa',
  seats: 30,
  reserved: 20,

  makeReservation: function{
    return this.seats - this.reserved;
  }
}
```

- in this example 

  + "object" is 'restaurant'.

  + "key" is 'name', 'seats', and 'reserved'.

  +  "value" is 'baracoa', '30', '20'.

**[name,seats,reserved] = properties**

**[makeReservation function] = method**

> ## Chapter 5 -Document Object Model :ambulance:

- DOM = Document Object Model

- It's called a DOM tree and are made up of 4 major nodes

> Document node

> Element node

> Attributr node

> Text node

- These elements can be accessed or selected in various ways.

  each of these methods will have a different function.

>> *example*

```js
getElementById() = 'selects elements by their specific id';

guerySelector() = ' this will select and return the first matching element by using a CSS selector';
```

- NodeList = lets you store a group or collection of nodes. Each of them will have an index number.


