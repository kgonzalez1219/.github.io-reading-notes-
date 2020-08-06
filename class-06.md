# Class Six Reading Notes


## Object Literals

Objects group variables and functions together to create a model of something. Though, they go by different names.

Variables are called **Properties** while Functions are called **Methods**. 

Properties give you information about the object while methods describe tasks asscociated with the object.
Properties can be strings, numbers, booleans, arrays or other objects while methods are always functions.


Objects are a set of name/value pairs called **Keys**.

To create an object using literal notation you would start by creating a variable. This will be the name of the object. Then establish the properties, separating the keys from the values using a colon and the properties and methods with a comma.

To access a property or method of an object you use dot notation. You use the name of the object, a dot, then the name of the property or method. 
Square brackets can also be used.

Is this context, the dot is called a **Member Operator**. This is because the property on the right is a member of the object.

When using brackets, the name of the property or method goes inside the brackets. This notation is used whn the property nae has special characters or numbers in it.

## Document Object Model - DOM

The **DOM** specifies how browsers should create a model of an HTML page and how JavaScript can go about changing the information on the page. 

It cover two major key points -

* Making a model of the page
* Accesing and changing the HTML Page

When a browser loads the page it creates what is called a **DOM Tree**. Which is specifies how the page should be structured.
It's called an object model because  the model is made of objects with each part of the page made up of different objects. 

The DOM is an **Application Programming Interface**, it lets humans interact with programs and lets the browser know how to alter the page.

Dom trees are made up of things called **Nodes**. Four of them to be exact.

* The Document Node
* Element Nodes
* Attribute Nodes
* Text Nodes

Each node is an object with methods and properties. These are accesed and altered by the script. 

### Document Nodes

The  document node is the first node on the DOM tree and the first node you go through to access any other node.

### Elemnt Nodes

To access the nodes you want in the dom tree, you start by targetign the element you want first.

### Attribute Nodes 

Once you've targeted he element, you can then target the specific attribute linked to it.

### Text Nodes

You can do the same with text nodes. Text nodes are never children and are their own branch hwithin the DOM Tree.

## So how do I work with this DOM Tree?

There are two steps to accesing and updating the DOM Tree

1. Locate the Node that qrepresents the element you want to work with.
1. Use its text content, child elements, and attributes. 


To access the elements there are three methods, DOM queries and Traversing the DOM. 
These consist of targeting individual nodes, multiple nodes or traversing through the element nodes. 

Some examples include : 

`getElementById()`
`getElementsByClassName()`
`parentNode`

Once you've targeted the element, you can use the methods and properties to update the page.

**DOM Queries** 

Methods that find elements in the DOM tree are called DOM queries. If you need to work with an element more than once, you should store the result of the query in a variable.
What you are really doing is storing the location of the element on the DOM tree in the variable. This gets rid of alot of work. The term for this is storing a **Reference** to the object in the DOM tree.

A collection of nodes is a **Nodelist** . The numbering in a nodelist is similar to an array in that it starts at 0. The order they are stored in the list is the same order they appear in the HTML document. Despite this, they are collections, not arrays.

When a  nodelis tis updated by the script, this is called a **LiveNodelist** and is considered faster than a **Static Nodelist**, which is a list that is not updated by the script.

`getElementByElement()` is the quickest and most efficient way to access a single element as no two elements should have the same ID. 

`querySelector()` is better as it uses css selectors. 


## Slecting an Element From the NodeList

You can select an element two ways.

* The item() method
* Array syntax

item() returns an individual node from the list. You do this by specifying the index number. 
Array syntax is preffered, because it is faster.


EWhen you have a Nodelist you can loop through each item in the collection and apply the same statements to each. This involves finding out the length of the collection and setting a counter to loop through them. 


## Traversing the DOM

When you have an element node you can select another element in relation to it using these five properties. 

- parentNode
- previousSibling/nextSibling
- firstChild/lastChild

Traversing the DOM can be difficult because some browsers add a text nde when coming across whitespace.


## Finding/Updating Element Content

When working with a textNode, you use the nodeValue property. This can be used to return the value of the textNode as well as update it. 

textContent allows you to collect or update just the text that is in the containing element and its children.

Theres also this thing called innerText, but we're gonna ignore that. 

## Adding/Removing HTML Content

The two methods for adding/removing HTML content are

- innerHTML property
- DOM Manipulation

innerHTML can be used to both retrieve and replace content. To do this, store new info in a string in a variable. Select the element and set the innerHTML property to the string. 

DOM manipulation targets individual nodes on the DOM Tree. 


## Cross Site Scripting

Yo, this is bad.

This is when your site is opened up to attacks because of tinnerHTML Use. 



## MISC>

Once you have an element node you can use properties and methods to change its attributes. To do this, select the element node that carries the attribute and follow it with a dot. Then uses a method to change its attributes


## Understanding the problem domain is the hardest part of programming.


Learning to program has a steep learning curve. 
The Problem Domain!!!! Dun Dun DUn!!~!!

- Simple Functtionality
- Easily explained
- Easily understood

Strip away complexity - simplify iy down to make it more manageable

Writin g code becomes easier when you understand the domain. 

**Understanding the problem is the most critical part of the equation**

So either make it easier, or get better at understanding the problem.

Do it right the first time. 



















