# Ducket HTML and CSS Book

## Links (Chapter 4)
 - ``<a>`` element is used to create links
 - href is hyperlink reference
 - ``<a href="web page you are linking to">Text to display</a>``
 - __Absolute__ URL's/web pages are when you type in the full site name: http://www....
    - Example: ``<a href="http://www.google.com">Google</a>``
 - __Relative__ URL's/web pages are when you are linking to files within your site, so you can just type the file name. 
    - Example: ``<a href="movies/dvd/reviews.html">Reviews</a>``
    - you will need to add folder details if the file is not in the same folder
 - __email__ is mailto:
    - Example: ``<a href="mailto:jon@gmail.com">Email Jon</a>``
 - __target__ will open a new window when the link is opened
    - Example: ``<a href="http://www.google.com" target="_blank">Google</a>``
 - linking to another part of the page requires creating id and a symbol I don't know how to create, similar to a not equals sign

## Layout (Chapter 15)
 - __Block elements__ start on a new line of text: 
    - Example: ``<h1> <p> <ul> <li>``
 - __Inline elements__ flow in between surrounding text
    - Example: `` <img> <b> <i>``
 - __Containg elements__ are when block elements are inside other block elements, creating a "containing" or "parent" element as the outer most element.
 - __Positioning Schemes__ allow you to control the layout of the page
  - __position: static__ is the default and does not need to be defined in CSS
  - __position: relative__ allows you to move an element compared to the default static
  - __position: absolute__ eliminates that elements impact on all other elements on the site.
  - __position: fixed__ will secure that element to a location, commonly used to keep in an element in view while scrolling given the element will not move on the screen
  - __z-index__ will define how elements overlap each other given the default is the element lower down in the code will be on top of earlier elements.
  - __float__ is an inline element that will move to the far left or right within that element. always add width to determine how much of the parent element you want the float element to utilize
  - __float multiple elements__ allows multiple paragraphs to align in columns across the page. although this will relocate the order as screen size is changed.
    - Example: p{ width:230px; float:left; margin: 5px; padding: 5px; background color: grey;}
  - __clear__ allows you to say that no element (within the same parent element) should touch the left/right sides of the box
  - __columns__ multiple ``<div>`` are needed within a block element, which are then floated.
  - __fixed width layouts__ don't stretch and contract, adjusting the layout of the elements as they are viewed in different pixel dimensions given the users screen. 
  - __liquid layouts__ stretch and contract, adjusting the layout of the elements as they are viewed in different pixel dimensions given the users screen. 

  # Ducket JS and Jquery Book

## Functions, Methods and Objects (Chapter 3, p 86-99)
 - Functions, methods and objects are used to help organize code.
 - __Functions__ is a group of statements that perform a specific task.
 -__Callling__ a function is when you are asking that function to perform its code.
   - Example: ``sayHello();``
 -__Parameters__ is information that is needed within a function that is passed to it from outside the function.
   - Example: ``function getArea(width, height){return width * height;}``
      - the parameters of width and height are within the () 
 -__Return Value__ is the response you get from the function when it has run its code.
 - __Declaring__ a function is used by started with the word __function__ and then adding a custom __function name__
   - Example: ``function sayHello() { document.write('Hello!');}``
 - Functions can return more than one value using an array

  # 6 Reasons for Pair Programming
   - __Pair Programming__ is having two programmers code together, simultaneously: "two heads are better than one"
   - __Driver__ will be the only one that is writing code and the __Navigator__ will only provide guidance and perform research on their own computer.
   - __4 skills__ to learning include: __Listening, Speaking, Reading and Writing__
   - Although creating the code in pairs takes slightly longer, the quality of the code is significantly better, taking less time overall to debug to create working code.
   - Progammers have a better experience when working in pairs given the social interaction and less time debugging or asking for help from a teacher.
   - Learning problem solving techniques from others given different experiences and thought processes.