# welcome To Read14a page ..

**CSS Properties ..** 

***Transform***

*The transform property allows you to visually manipulate an element by skewing, rotating, translating, or scaling:*

***Example:***

`.element {`
  `width: 20px;`
  `height: 20px;`
  `transform: scale(20);`
`}`

**Values:**

1. scale(): Affects the size of the element. This also applies to the font-size, padding, height, and width of an element, too. It’s also a a shorthand function for the scaleX and scaleY functions.

2. skewX() and skewY(): Tilts an element to the left or right, like turning a rectangle into a parallelogram. skew() is a shorthand that combines skewX() and skewY by accepting both values.

3. translate(): Moves an element sideways or up and down.

4. rotate(): Rotates the element clockwise from its current position.

5. matrix(): A function that is probably not intended to be written by hand, but combines all transforms into one.

6. perspective(): Doesn’t affect the element itself, but affects the transforms of descendent elements’ 3D transforms, allowing them all to have a consistent depth perspective.

![img](https://i.ytimg.com/vi/OJWz-cX8haA/hqdefault.jpg)

***Transitions***

*provide a way to control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time. For example, if you change the color of an element from white to black, usually the change is instantaneous. With CSS transitions enabled, changes occur at time intervals that follow an acceleration curve, all of which can be customized.*

![img](https://miro.medium.com/max/900/1*_6MfwckxNfQTca9SiG8MdQ.png)

***Animation***

*The animation property in CSS can be used to animate many other CSS properties such as color, background-color, height, or width. Each animation needs to be defined with the @keyframes at-rule which is then called with the animation property, like so:*

***Example:***

`.element {`
 `animation: pulse 5s infinite;`
`}`

`@keyframes pulse {`
  `0% {`
    `background-color: #001F3F;`
  `}`
  `100% {`
    `background-color: #FF4136;`
 ` }`
`}`

![img](https://i0.wp.com/codemyui.com/wp-content/uploads/2017/08/wave-text-animation.gif?fit=880%2C440&ssl=1)
