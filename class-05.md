# Ducket HTML and CSS Book

## Images (Chapter 5)
 - __align left or right__ left or right will allow images to be on the left or right side of the text if within the paragraph. This is done in html and is inside the same paragraph with the text
   - Example: ``<p><img src="" align="left"/>``
 - __align top or bottom__ will impact where the first row of text will be relative to the image. 
   - Example: ``<p><img src="" align="bottom"/>`` will usually be the best option to use given the first row of text will start at the bottom of the image, typically preventing gaps in the text compared to using middle or top.
 - __jpeg__ is the best format to save a picture if it has a lot of different colors within it to prevent loss of detail when displayed.
 - __gif or png__ is the best format to save pictures when you are using icons or very few colors/details in the file.
 - __vector images__ are drawn using coordinates/vectors so they can be scaled and the details filled-in as needed without degrading the quality of the icon.
   - Example: images that get blury as you increase their size are examples of images that are not using vectors, if they were, the icon would not get blury as you incrase the size. 
 - __animated gifs__ are multiple frames of an image and therfore can be used to create simple animations.
   - Example: the hourglass icon on your computer while it is thinking. It's simply a couple of images, that show a couple different stages of progress, that are repeated
 - __fig caption__ allows you to write a sentence under the image
 

## Color (Chapter 11)
 - __3 color properties__ RGB, HEX Codes and 1 of 147 predefined color names: red, white, blue,...
 - __opacity__ will allow you to see through an element, 100% being completely see-through
 - __Hue, Saturation, Lightness__ Hue is the color, saturation is the amount of gray in the color and lightness is the amount of white/darkness in the color.

## Text (Chapter 12, p 86-99)
- __sans-serif__ is simple text
- __serif__ has extra details on each leter, looking more fancy
- __monospace__ will seperate every letter evenly
- __:link__ will show a style to a link that you have not yet visited
- __:visited__ will show a different style(blue clicked on color) that shows you have already visited on that link.
- __hover__ will change the appearance when the user moves their mouse over the element
- __active__ once the use selects an item, this will change the apperance of that item
- __focus__ is when your mouse is in an element, text box for example, and you mouse changes from a pointer to a "I" showing that you should start typing
- __attribute selectors__ create rules that apply to elements that have an attribute defined.

