# Chart.js

Charts!!! They're Exciting!

**Chart.js** Is an HTML5 Plugin used to draw a graph onto your page.

We're talking allll the charts. Line, bar, pie! So many charts, it's off the charts!

This is useful and can be implemented to showcase groups of data on your webpage!


To start, download that puppy, then put it inside a canvas element within your html file. (in the body) Then, write a script that will retrieve the data. Then we need to create our data with an object.




## Basic Usage

The canvas element is similar to the img element but without an src or alt, can be styled within the tag or through css.
This creates fixed size drawing surface that exposes a rendering context......whatever that means. 
The canvas starts blank and render content through a script.
It does this with the getContext() method. It takes one parameter which is the type of context. 

## Drawing Shapes

**Tha Grid!!!** 
The grid starts at 0,0 in the top left corner. Everything after that is positioned relative to these coordinates. 
Canvas supports two shapes. Rectangles and Paths. (points connected by lines.)

There are three functions that draw rectangles. (fillRect, strokeRect, and clearRect)
Ech of the m are used to create the out;line, clear out space from and draw an outline respectively.

**Paths!**
Steps to create a path - 
1. create the path
1. Use drawing commands to make the path.
1. Stroke or fill to render the path

Functions used to do this
- beginPath()

Mthods - 
- closePath
- stroke
- fill

An moveTo is also useful in moving points or draw unconnected paths.

lineTo is used to create.....Lines!!!! Cue airhorn and lazers!
 styles and color are similarly applied using functions and methods. Some examples are as follows - 

 - lineWidth
 - lineCap
 - lineJoin
 - getLineDash
 etc.


 You can also style the ends of line using properties such as butt, round and square.

 Text is also similar with methods like

 - fillText, 
 - stroketext.

 To style you can use, 

 - font
 - textAlign
 - textBaseLine
 etc

 






