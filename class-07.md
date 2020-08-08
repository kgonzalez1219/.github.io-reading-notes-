# Class 07 Reading Notes


## Tables

A table represents information in a grid format. Each block in the grid is reffered to as a table cell. 

### BAsic Structure -

To create a table you start with the `<table>` element. Add rows with the `<tr>` element and cells with the `<td>` elemnt.  For headings you use the `<th>` elemnt.

To have the content of a column you use the colspan attribute and rowspan for rows. 

The ` <thead>, <tbody> and <tfoot> ` elements are used to distinguish the start and end of the table.


## Functions, Methods and Objects - 

**Constructor Notation** Dun DUn DUUUUNN!!!

Using the new Keyword and the object constructor function, you can create a blank object and start putting things into it. Each property within this object should end with a semi colon. 

To update a property use dot notation to give an aalready existing property a new value. You can also use bracket notion. (Only for properties, not methods).

To delete a single property, use the **delete** keywords before the property name, whereas you can leave the value empty to clear the property.t

## Many  Objects!!!

Object Constructors use a function as template for creating objects. To do this, first create the template with the properties and methods. 

You create **instances** of the object using the constructor function. The **new** keyword followed by a function creates a new object. The properties of each object are given as arguments to the funtion. 

So each time the function is called the arguments will be different because they will be for different objects. Though each object will have the same method. This is because the method accesses, updates or performs a calculation on the data within the properties. 

Once the instances of the objects have been created their  properties can be accesed using dot notation. 

## This! < -- It's a keyword

This usually refers to the object in which it operates.
When a function is at the top of the script, it has **global scope**. When a function is defined inside an object it is a **method** 

Arrays are objects. They hold key/value pairs, but the key for each value is its index number.
Arrays and objects can be combined to create complex data sets. arrays can store objects and objects can store arrays. 

## Built in Objects - 

Browsers have built in objects, such as the browser window, and current web page. The functionality of these objects is usually needed by many different scripts. 

The three componants of the built in object toolkit:

1. The browser object Model
1. The Document Object Model
1. Global JAvascript Objects

An **object model** is a group og objects that represent related things from the real world that come together to form a larger model. 

Objects can be nested inside other objects, these are called **child objects**

The browser object model creates a model of the browser tab or window. 
The document object model creates a model of the current web page. 
Global objects don't form a single model. 
the names of global objects start with a capital letter& the string objects.


## Domain Modeling - 

Domain Modeling  is the process of creating a conceptual model in code for a specific problem. A well built domain model can verify a nd validate your understanding of the problem. 

An **object oriented model** is something that stores data in properties and keeps behavior in methods. 

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

* Model its attributes with a constructor function that defines and initializes properties.

* Model its behaviors with small methods that focus on doing one job well.

* Create instances using the new keyword followed by a call to a constructor function.

* Store the newly created object in a variable so you can access its properties and methods from outside.

* Use the this variable within methods so you can access the object's properties and methods from inside.





