## Domain Modeling
 - __Domain Modeling__ is the process of creating a conceptual model in code for a specific problem.
 - __object-oriented models__ is an entity that stores data in properties and encapsulates behaviors in methods.
 - __new__ keyword instantiates (creates) an object

### Domain Modelin Tips
 1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
 2. Model its attributes with a constructor function that defines and initializes properties.
 3. Model its behaviors with small methods that focus on doing one job well.
 4. Create instances using the new keyword followed by a call to a constructor function.
 5. Store the newly created object in a variable so you can access its properties and methods from outside.
 6. Use the this variable within methods so you can access the object's properties and methods from inside.

## Ducket HTML Book
### Tables (Chapter 6, pages 126-145)
 - ``<table>``
 - ``<th>`` table heading, treated as a row
 - ``<tr>`` table row, start of each row
 - ``<td>`` table data, each cell of that row
 - __span__ has the effect of merging across multiple columns or rows
    - ``<td rowspan="2">Geography</td>`` will span/merge across two rows
    - ``<td colspan="2">Geography</td>`` will span/merge across two columns

## Ducket JS Book
### Functions, Methods and Objects (Chapter 3, pages 106-144)
 - __this__ is used to refer to the object in which the function operates
 - Arrays and objects can be combined to create complex data structures
 - __built-in objects__ browsers come with a set of built-in objects. There are three groups of built-in objects.
    - Browser
    - Document
    - Global Javascript
 - __Window Objects__
    - __window properties__ will define the information about how the information is displayed and dimensions of the window
        -Example: __window.innerheight__ is a property of the window height
    - __window methods__ will determine how the window operates
        - Example" __window.alert()__ will create a dialog box with a message requring to select OK
 - __String Objects__ whenever you have a value that is a string, you can use the properties and methods of the string object on the value
    - Example: __toUpperCase()__ will changed all the characters in that string to Uppercase.
 - __Number Objects__
    - Example: __isNaN()__ checks if the value is not a number
 - __Math Objects__ does math stuff
    - Example: __Math.round()__ rounds number to the nearest integer
 - __Date Objects__ set and retrieve time and date
    - Example: __getMonth()__ returns sets the month (0-11), note month zero is january
    


