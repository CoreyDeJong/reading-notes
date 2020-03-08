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
For Example:
^The        matches any string that starts with The -> Try it!
end$        matches a string that ends with end
^The end$   exact string match (starts and ends with The end)
roar        matches any string that has the text roar in it

3 main purposes
1. Testing

* Built-in Javascript


Summary:
* data validation (for example check if a time string i well-formed)
* data scraping (especially web scraping, find all pages that contain a certain set of words eventually in a specific order)
* data wrangling (transform data from “raw” to another format)
* string parsing (for example catch all URL GET parameters, capture text inside a set of parenthesis)
* string replacement (for example, even during a code session using a common IDE to translate a Java or C# class in the respective JSON object — replace “;” with “,” make it lowercase, avoid type declaration, etc.)
* syntax highlightning, file renaming, packet sniffing and many other applications involving strings (where data need not be textual)