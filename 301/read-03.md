## Handlebars
 - handlebars.js is a template engine based on the Mustache template language
 - any data that you print out in an {{ }} expression, will automatically get HTML escaped by handlebars. . 
 - {{{}}}Triple curly braces are used when you wish to print raw HTML
 - Context - the object where properties you include in curly braces are looked up. Every template you write has a context. On the top level, this is the JavaScript object that you pass to the compiled template. But helpers like #each or #with modify it, so that you can access the properties of the iterated object directly. The next example will make things clearer.
 - Handlebars doesn't allow you to write JavaScript directly within templates. Instead, it gives you helpers. These are JavaScript functions that you can call from your templates, and help you reuse code and create complex templates. To call a helper, just use it as an expression - {{helpername}}. You can pass parameters as well - {{helpername 12345}}, which are passed as parameters to your helper function.
 - Block helpers are just like the regular ones, but they have an opening and a closing tag (like the #if and #each built-ins). These helpers can modify the HTML and content they are wrapped around. They are a bit more complicated to create, but are very powerful. You can use them to reuse functionality or to create large blocks of HTML in a reusable way (for example lists of items that you use on many places in your app).

## Flexbox
 - The Flexbox Layout aims at providing a more efficient way to lay out, align and distribute space among items in a container, even when their size is unknown and/or dynamic (thus the word "flex").
 - You can easily control the layout by using flex-direction, order, flex-grow, flex-wrap, flex-shrink, flex-basis, justify-content, flex, align-self, align-items and align-content