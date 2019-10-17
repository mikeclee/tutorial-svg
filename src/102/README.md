
## AnimateTrasform Guide

* `type`="rotate"
Animate rotation, as opposed to scaling or translating
* `from`="0 150 150"
* The coordinates of the animation starting point. The first of the three values is the initial degrees of rotation, while the second and third values are the x and y position of the center. We start at 0 degrees of rotation, and set the center to 150 in both directions as that position is right in the middle of our 300 by 300 shape.
* `to`="-360 150 150"
* The coordinates of the animation finishing point, again representing degrees of rotation and the center’s x and y position. We leave the center at the same position, and set the finishing degrees of rotation to -360 for a full rotation. The negative value makes the rotation turn counter-clockwise, in the direction the arrow is pointing.
* `begin`="0s"
* Setting this value to 0 seconds means the animation will start right away. If a positive number were used it would cause a delay in starting the animation.
* `dur`="10s"
* Here we set the duration to 10 seconds so the animation has a fairly slow pace.
* `repeatCount`="indefinite"
* Setting this value to indefinite means the animation will loop endlessly

## ViewBox Guide

* Adjust the viewBox values on the opening svg tag to -20 -20 340 340.

* The first two numbers control the “panning” of the shape, and the last two numbers control the “zooming”.

## Reference

* [Create an Animated SVG (2019-03)](https://webdesign.tutsplus.com/tutorials/create-an-animated-svg-logo-for-international-womens-day-2019--cms-32875?_ga=2.79214359.2099313500.1571197917-1858917272.1571197917)
* [How to Create a Loader Icon With SVG Animation
 (2018-07)](https://webdesign.tutsplus.com/tutorials/how-to-create-a-loader-icon-with-svg-animations--cms-31542)
* [Figma online tool](https://www.figma.com/)
