# Reading 03

**HTML and CSS**

There are different types of lists you can use in your HTML files.
 - Unordered: lists made wihtout using numbers
 - Ordered: lists made using numbers in chronilogical order
 - Definition: lists made to show a series of terms and their definitions
 - Nested: lists made to be a sublist within a list element to elaborate on a list item. (these do not require a tag..)

CSS treats each HTML element as if it lives in it's own box. You can use CSS to decorate these said "boxes".
 You can make them dotted, spotted, or just simply changed the size of them. You can hide elements using the display and visibility properties. Block-level boxes can be made into inline boxes, and those boxes can be made itno block-level boxes. They can also be used to hide an element from the page. The values that these properties can take: 
  - inline: causes a block-level element to act like an inline element
  - block: causes an inline element to act like a block-level element
  - inline-block: allows a block-level element to flow like an inline-element.
  - none: hides an element from the page\

The visibility property lets you hide boxes from users, but will leave a space where the element would have gone. ( leaving muuuch to the imagination)

you can use two properties to achieve this
 - hidden- hides the element.....(who would have thought of that...)
 - visible- this shows the element........(captain obvious)

You can use the border-image property which can add a border to any box. it takes a background image and slices it into nine pieces. This requires three pieces of information:
 - the url of the images
 - where to slice the image
 - what to do with the straight egdes; the values are
   - stretch- stretch the image
   - repeat- repeats the image
   - round- like repeat, yet if the tiles don't fit exactly, scales the tile images so they will. 

The property box-shadow lets you add a drop shadow around the box:

These are the values this property should use
- Horizontal offset:  negative values put the shadow to the left of the box
- Vertical offset: negative values put the shadow at the top of the box
- Blur distance: if omitted, the shadow is a solid line like a border
- Spread of shadow: if this is used, a positive value will cause the shadow to expand in all directions.

You can also use whats called a border-radius to make rounded corners and elliptical shapes and legibility can be improved by controlling the width of boxes containing text and the leading.


**JavaScript**

An Array is a special type of variable. It can store a whole list of arrays. To create an array you would give it a name like any other variable.
There are two techniques for creating an array:
 - array literal- values assigned to the array inside of a pair of square brackets and each one is seperated by a comma.
 - array constructor- uses a new keyword followed by Array(); the values are then specified in parenthesis (not by square brackets), and these values are seperated by a comma.

Values within an Array are accessable if they are within a numbered list and know that the start of this list **should be a zero not a one.**
Each item in an array is given a number called an index. To access a value in an array, after the array name you would specify the index number for the value inside the square brackets and to change a value in an array you must select it and assign it to a new value just as you would any other variable.

**Expressions and Operators**
- Expressions evaluate into a single value. There are two types of expressions
  - expressions that just assigns a value to a variable
  - expressions that use two or more values to return a single value
- Expressions rely on Operators; they allow programmers to create value from one or more values.

*If..Else Statements*

These statements check a condition.
(if it resolves *true* the first code block is executed)
(if it resolves as *false* the second code would then run instead)

*Switch Statements*

This statement starts with a valuable called the switch value. Every *case* indicates a possible value for this variable and the code that should run if the variable matches the value. These *switch statements let you compare a value against possible outcomes. 

- Falsy values are treated as if they are false......
- Truthy values are treated as if they are true.....
This is due to whats cakked a Type Coercion. Where if you use a data type in JavaScript that it did not expect it will try to make sense of it so, every value in JavaScript can be treated as if it were a true or false.

*Loops*

Loops check a condition. If it returns true a code block will run, but if it returns false then thats the end of the loop.
There are three types of loops:
 - for- runs a specific number of times
 - while- use this when you dont know how many times you need it to run
 - do while- it is like the while loop but the only difference is it will run the statements inside the curly braces atleast once, even if it is false

[<==Back](README.md)