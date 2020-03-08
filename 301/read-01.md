### Shay Howe's Intro to RWD
* RWD = Responsive Web Design. Websites for all size screens.
* Responsive and adaptive is to quickly change
* 3 Components:
1. Flexible layouts - grid can dynamically resize to any width, most commonly by using % or em.
1. Media Queries - specify different styles for different browsers/circumstances.
1. Flexible Media - adjusting the size of images, video, canvas as screen sizes change

* mobile first should be used when designing a website
* viewport meta tag should be used for mobile devices to define the device-height and device-width

### All About Floats
* Floats can be None (default), Left, Right or Inherit (assumes parent element)
* Clear: both; can be used to ensure an element is not affected by float
* Parent elements will collapse if the child elements are all floated.

### Don't Overthink it Grids
* `box-sizing: border-box;`will keep the element within the defined element width, any additional padding or borders will shrink the size of the context to maintain the same overall width, excluding margin

### CSS Floats Explained By Riding An Escalator
* floats create alternative flows: normal, left, right
* Clear property allows elements to specify where they should align in comparison to the floated elements. 
* "Clear:left" tells each element floating left that they should align themselves behind the first element that is floated left.
* "Clear:both" will tell the floated elements to float behind the elements that have the same float left/right.