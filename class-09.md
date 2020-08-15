# Class 9 Reading Notes

## Forms

So ya wanna collect information from your users? Then you need a **Form!**

You can use HTML to create not just forms, but buttons, search boxes and more!

### Form Controls - 

Types of form controls:

- Adding Text 
  1. Text input
  1. Password input
  1. Text area
- Making Choices
  1. Radio Buttons
  1. Checkboxes
  1. Drop Down Boxes 
- Submitting Forms
  1. Submit buttons
  1. image Buttons
- Uploading Files
  1. File upload

  A form can have several controls, collecting different bits of information. 

  So how does a form work?
   1. The user fills it in and clicks on the submit button.
   1. The name og each form is sent to the server with the value entered by the user. 
   1. The server processes the information using a programming language. 
   1. The server creates a new page to be sent back to the browser. 

   That simple!



  You star with a `<form>` element, it should always have the action attribute, and will usually have methods and an id as well. 

  Action - Every form must have an action attribute. It is the url of the page on the server that will recieve the information. 

  There are two methods for sending forms

  **Get** - With this method values are added to the end of the url in the action attribute. It's good for short forms and retrieving data from the server. 

  **Post** -  With this method theh values are sent in HTTP headers. Use the post method if your form allows users to upload a file, is log, contains sensitive data, or adds/takes away info from a database. 


  An Id is used to identify the form from other elements on the page.

  The `<input>` element can be used to create several different controls. It uses the type attribute to do ths.

  - Text - creates single box for text input.
  - name - Identifies form control
  - maxlength -- Limits number o fcharacters allowed in text field. 
  - Password - Creates a single textbox, but with characters blocked out. 


  Text area - Creates multi line text box. Needs an opening and closing tag. You can use these to put text into the text box. 

  Radio Button - These let users select one option put of many. 
  Check Box - Allows user to select more than one option. 

  - Drop down list - 
  Allows users to select an option from a drop down list
  File input box - Lets users upload a file. 
  - submit button - Sends form to server. 


Button 

The button element gives you greater control over how your button looks, by letting you put info in between the opening and closing tags. 


  ## Lists, Tables & Forms

You want some pretty bullet points? Or a nice border or background?

For bullet points you use the **list-style-type** property. If you want to use an image you'd use the **list-style-image** property.
For positioning use **list-style-position**


#### Table properties
- width
- padding
- text transition
- letter spacing
- boder top, border bottom
- text align
- background color
- hover


To show the boder on empty cells, you use the **empty-cells** property. If you want spacing between cells use **border-spacing*** or **border-collapse**.

#### - Styling Forms 

- font-size
- color
- background-color
- border
- border-radius
- background-image

#### Styling Submit Buttons

- color
- text-shadow
- border-bottom
- background-color


#### Cursor

- auto
- crosshair
- default
- pointer
- move
- text
- wait
- help
- url(gursor.gif):




## Events

Interactions creates events, which trigger code, which then responds to users. 

There are many different events that can happen while browsing. 

The steps taken to trigger an event are called **Event Handling** 

1. Select the elemnt you want the script to respond to. 
1. Indicate which event will trigger the response
1. State the code you want tyo run when this occurs. 

Ways to bind an evetnt to an element- 
- HTML event handlers
**This is bad** 
Early HTML had attributes that could respond to events on the element they were assigned to. This is no longer used because JS is separated from the HTML. NOt going in depth, because.... it shouldn't be useed.

- DOM event Handlers 
Considered better than HTML handlers, because they allow for separation of JS and HTML. However you can only attach a single functoin to to any event. This can be code breaking. 

- DOM level 2, event listeners
Favored, These can deal with more than one funtion at a time.

Using Parameters with event handlers and listeners - 
You can't use parentheses with these things, so you have to use an **anonymous funtion**


**Event Flow** 
When you hove and click on a link, you are also clicking on its parent elements. The order in which events fire is the event flow. This can go in two directions. 

**Event Bubbling**
Event starts at most specific node and flows outward.
**Event Capturing**
Event starts at least specific node and flows inward. 

Flow only really matters hwn you have handlers on an element and one of its ancestors. 

**Event Object** 
When an event occurs the event object tells you info about the event and the element it happened on. 

**Event Delegation**
By using event delegation you can speed up the load time of a page. Insted of placing a listener on many elements, you can place it on the parent element.







