# Ducket HTML Book

## Lists (Chapter 3)
 - Ordered List ``<ol>``
 - Unordered List ``<ul>``
 - Definition List: terms along with the definitions for each of the terms.
    - ``<dt>`` for the term
    - ``<dd>`` for the definition
 - Nested lists are lists within a list

## Boxes (Chapter 13)
 - Margin is the outermost property of a box, commonly used to define the space between the border and other objects
 - Border is the middle property of a box, commonly used to define a box around an object
 - Padding is the inner most property of a box, commonly used to define the space between the text and the border
 - border-image property applies an image to the border of any box
 - box-shadow property allows you to add a shadow around a box
 - you can use inline, block, inline-block to make html blocks to style like inline, block or inline/block elements
 - visibility: hidden; will hide boxes but leaves a space where the element would have been
 - border-radius will allow 1-4 of the corners to have a radius while the other 0-3 corners are square

### Common Box Code
 - border-width: thin or medium or thick,...
 - border-style: solid or dotted or dashed,....
 - border-color:
 - shorthand code = p{border: 3px dotted #0088dd;} will define the width, style and color of a border
### Padding Common Code
 - padding: p{padding:10px;} will add 10px of white space around the text in the paragraph from the border
### Margin Common Code
 - margin: p{margin:20px;} will add 20px of white space around the border from other boxes
 - centering a box in the middle of a page or element:
   - margin-left: auto
   - margin-right: auto
   - shorthand p{margin: 10px auto 10px auto;} the four quantities are the four sides of the box, with the left and right being set to auto

# Ducket JS Book

## Decisions and Loops (Chapter 4)
 - switch statement are similar to if/else statements, just easier to develop if multiple conditions are needed
 - switch value is the start of a switch statement
 - Case is a possible value for the switch variable and will run that code if there is a match
 - Default is the final case that will run if none of the cases match
 - Type coercion is the ability of Javascript to try to understand numbers vs. strings vs booleans,....if not properly defined compared to other languages reguire clear definition.
 - NaN is not a number
 - loops check a condition, if it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again, repeating until the conditon returns false.
 - For loops are used when you want code to run a specific number of times.
 - while loops will continue to run until it gets a false statement.
 - for loops uses a counter as a condition that is made of 3 statements: initilatization ``var i =0;``, condition ``i<number;``, update ``i++``
