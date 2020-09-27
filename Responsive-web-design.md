# Intro to Responsive Web Design 

The growth of the internet has been exponential with mobile internet usage being a large portion of it. 

This has posed the question of how to make webssites for all devices, with **responsive web design** being the answer. 

According to  learn.shayhowe.com, Responsive web design is the practice of building a website suitable to work on every device. 

RWD is design that dynamically adapts to different viewports and browsers. It can be broken down into three parts. 

- Flexible layouts
- Media QUERIES
- Flexible Layout

## Flexible Layouts

This measn the site is built on a flexible grid using relative length units. These are then used to declare common grid property values like **width**, **margin** and **padding**.

There is a formula used to identify the proportions of a flexible layout using  relative values. 

**target ÷ context = result**

Flexible layout won't work on its own. As you may have instances when the viewport is so small the content stacks on itself and becomes unreadable.
This is when using **Media Queries** comes in. 

## Media Queries

Media queries give one the ability to specify different styles for individual browser and device circumstances. 

some ways to incorporate these into your code are

- @media
- @import
- Linking to a separate style sheet from the html.

Its reccomended to use @media. 

## Flexible layout

The final componant is flexible media. This means that images, videos and other media types should be scalable. One way to do this is by using the max-width property with a 100% value. 

This will not work for iframes and embedded media. To fix this, the elements should be absolutely positioned with a parent element. 


# Floats

**Float** is a css positioning property. It hearkens back to print text, which utilized "text wrap".

Elements with the float property applied to them are similar to images within print layout, as the text flows around them. 

**Absolutely positioned** elements are removved from the flow of the page. They do not effect the positioning of other elements. 

The four values for float are:
- left
- right
- none
- niherit

Float is useful in that, if an element changes size, the content will flow around it. 

Float has a sister property called **clear**. An element with clear will not move up adjacent to the float like the float desires, but will move itself down past the float. 

clear has four values:
- both
- left
- right
- none


If the parent element contians nothing but floated elements, it will literally collapse. This should be dealt with to prevent cross browser problems. This is fixed by clearing the float after the floated elements in the containerbut before the close of the container. 

### Clearing your floats 

- Empty Div 
- Overflow
- Easy clearing


Problems - 

- Pushdown
- Double Margin
- 3px Jog
- Bottom Margin Bug

misc. notes - 
Floats create alternate flows. There are left, right and center flows & elements not floated can fill the space not taken by floated elements.

# SMACCS

Scaleable and Modular Architecture for css

Allows structuring for css for flexibility and maintainability.

- base
- layout
- module
- state
- theme
