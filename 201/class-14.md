### CSS Transforms
 - __Transform__ will change elements size and position, either 2D or 3D.
 - 2D transforms:
    - ``transform: rotate`` for rotating clockwise or counter-clockwise
    - ``transform: scale`` to increase or decrease the size
    - ``transform: translateX`` will move the item along the x-axis, can also be done for y-axis or both
    - ``transform: skew`` to create a parallelogram
    - ``transform: perspective`` to create a trapezoid aka the star wars intro
 - 3D transforms:
    - Example : ``.box-1 {transform: perspective(200px) scaleZ(1.75) rotateX(45deg);}``

### CSS Transitions and Animations
 - __Transitions__ change from one state to another
    - the easiest way for determining styles for differnt stais is using hover, focus, active and target.
    - not all properties can be transistioned, there must be ways to define mid-points throughout the transition. Color and size are the best examples on how you can transistion from one color/size to another color/size.
    - there are four transition related properties, not all are required:
        1. transition-property
        2. transition-duration
        3. transition-timing-function
        4. tranistion-delay
 - __Animations__ will have multiple states of changes
  - ``@keyframes`` is how you define when an animation will change
  - an animaation name is needed to name each keyframe
  - __animation iteration__ is how many times the animation will run, default is only once
  - __animation direction__ will allow the script to run in reverse if you set an infinite iteration
  - __animation play state__ will allow the animation to stop if the user interacts differently with the animation
  - __animation fill mode__ will determine how the animation is styled before/after the animation.



### 8 simple CSS3 transitions that will wow your users
1. Fade in: will change the color from lighter to/from darker
2. Change Color
3. Grow and Shrink
4. Rotate
5. Square to Circle
6. 3D Shadow
7. Swing: will make the item move back and forth like a swingset
8. Inset Border: will make a border appear

