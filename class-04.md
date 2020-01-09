# Ducket HTML Book

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