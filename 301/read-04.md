## CSS Grid
* CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system. You work with Grid Layout by applying CSS rules both to a parent element (which becomes the Grid Container) and to that element's children (which become Grid Items).
* To get started you have to define a container element as a grid with display: grid, set the column and row sizes with grid-template-columns and grid-template-rows, and then place its child elements into the grid with grid-column and grid-row. Similarly to flexbox, the source order of the grid items doesn't matter. Your CSS can place them in any order, which makes it super easy to rearrange your grid with media queries. Imagine defining the layout of your entire page, and then completely rearranging it to accommodate a different screen width all with only a couple lines of CSS. Grid is one of the most powerful CSS modules ever introduced.

Key Terms
* Grid Container - main container
* Grid Item - the children of the container
* Grid Line - the dividing lines that make up the structure of the grid, either vertical or horizontal
* Grid Track - an entire column or row of the grid that can span over grid lines
* Grid Cell - the space within defined grid lines
* Grid Area - a defined accumulation of cells defined by a custom set of multiple grid lines.

## RegExr (Regualar Expressions)
- Regex are extremely useful in extracting information from any text by searching for one or more matches of a specific pattern
- [] anything within brackets will be tested
- () everything within the parantheses must match exactly
- (?)will make anything match or not match
- anything not in () or [] will be required


3 methods to use with regex
1)regex.test(str). Returns true or false
2) str.match(bananas); will go through the bananas and return an array of all the matches
3) str.replace(regex, thing to replace it with), will return the new string

__Patter Flags__
`Patter flags` after the last `/` to determine how will impact the entire expression
- `/g` = global, will go through all instances, and not stop at the first time there is a match
- `/i` = insensitive, case insensitive

