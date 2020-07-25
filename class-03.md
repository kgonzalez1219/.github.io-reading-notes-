# Reading Notes- Class Three


## Lists

HTML gives you the choicee of three different **lists**. 

* Ordered Lists
* Unordered lists
* Definition Lists

Ordered lists are created by using the ` <ol> ` element. To populate it, you would uuse the ` <li> ` element. It is best to style these lists using CSS.

Unordered  lists are created using the ` <ul> ` element and are also populated using the ` <ul> ` element.

Deefinition lists are created using the ` <dl> ` element and are populated with the ` <dt> ` and ` <dd> ` elements to add terms and definitions. 

Lists can be nested within each other. 

## Boxes

CSS uses the **Box Model**. This means it treats each element as if it were in it's own box. This is important to pay attention to when considering the format and layout of your page. 

To size a box you satrt with it's **Height** and **width** dimensions. It is important to keep the design of your page flexible, both for future editing and for different types of screens that will be viewing the page. 
To to size a box you can use **pixels**, **percentages**, or **ems**.

You can specify how big or small you would like to keep your boxes. This can be done using  **min-width**, **max-width**, **min-height**, and **max-height**.These allow yoou to keep your boxes set to a specific size.
You can use **overflow** to handle content that is too big for a box. You can hide it or put it into a scroll box.

## Border, Margin and Padding

Border margin and padding are three properties that control the look and layout of a box. The border separates the edges of a box, the margni sits on the outside of the border and the padding is the space between the border and content of the box.

The space between items on a page is reffered to as **white space**, padding and margin is useful in adding whitespace where it is needed. 

When considering the width and style of your border it's important to remember **TRBL**, this stands for Top, Right, Bottom and LEft which are the properties  used to specify the border width. You can also just use thin, medium or thick. 
To style the boder you can use the following terms:

* Solid
* Dotted
* Dashed
* Double
* Groove
* Ridge
* Inset
* Outset
* Hidden or none

To center a box, set the left and right margin to auto.

You can turn an inline element to a block elemt or vice versa using the display property. It can also be used to hide an elemnt.
You can also use the visibilty property to hide things. This can be done with the **hidden** and **visible** properties.

## Decisions and Loops!

**If-Else Statements** - Check a condition. If it resolves to true, it runs the first code block. If it resolves to false, it runs the second code block.

**Switch Statements** - Uses a variablecalled a switch value. The comp runs through sevel possible values called Cases and runs the one that matches the variable.

**Type Coercion and Weak Typing** - These terms relate to JavaScript because of the way it evaluates information. When comparing values and using the ` == ` operator, Javascript can interpret a string to be a number for example.

This is reffered to as weak typing.

**Truthy and Falsy** - Every value in JavaScript can be treated as either true or false because of weak typing.

**Loops** - Loops check and recheck a condition until it returns false. 
Three type of loops are:

* For - for when you need to run code a specific number of times.
* While - For when you're not sure how many times to run the code.
* Do While - Similar to the while loop, will always run the code once even when evaluating to false.

**LoopCounter** - This instructs the loop to run a specified number of times. 

This works by -

* Initialization -Create your variable.
* Condition - Loop will continue until number is met.
* Update - Every time the loop is run, a number is added to the counter. 



