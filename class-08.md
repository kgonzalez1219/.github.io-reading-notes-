# Class 8 Reading Notes - 


Ch.15 LAYOUT!!!

Designing attractive layout for a screen is different than designing for print or other platforms. 

Key Concepts -

- Block level element
- Inline element

Block level elements always start on a new line, whereas inline flows along with the the text. Yo can control ho w much space an element take up using height, width, borders, margin and padding.

` <div> ` elements can be used to group together elements. When doing this, it is reffered to as the **containing element** .

You can control the positioning of elements using **positioning schemes** 
These are:

- Normal Flow
- Relative Flow
- Absolute Positioning

To use these you use the *position* property. You can aslo use float to float the property.


Block elements stack on top of each other by default, so you don't need to edit anything. You can use the ` position:static ` though.

to position something relative to where it would have been in normal flow, use ` position:relative `

When using ` position:absolute ` the box is taken out of normal flow and doesn't effect other elements. ` position:fixed ` is a type of absolute positioning. It positions the element in relation to the broowser window. 

## Float 

Float allows you to take an element in normal flow an dplace it to the left or right of the containing element and anything else that sits inside of the containing element flows around it. 
Float is often used to place elements side by side. 

 Float can be paired with left, right, both or none to indicate that no element should touch either side of the box. this is called float **clear**.

 You can use float to create a multi column layout. To do this, use a `<div>` to represent each column, then use width, float and margin to position them. 


 ## Screen Sizes and Resolutions

 Ideally you are designing a site that will be accessed by many different kinds of screens, with different resolutions. So you gotta keep that in mind. You want your layout to be *fluid*
.
Resolution is how many dots a screen shows per inch. Most handhelds have higher resolutions than desktops.

A good average for resolution is around 960 to 1000 pixels wide. 

Fixed width layout designs do not change as the user changes their creen size, while fluid layuots stretch and contract. Fixed layout use pixels while liquid layouts use percentages.

## - Grids

The most widely used grid used by web designers is the 960 pixel grid. 
Grids set consistent proportions and spaces between items. 



