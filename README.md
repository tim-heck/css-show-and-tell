# css-show-and-tell

CSS Drop Shadow

This CSS effect allows the an object to appear like it is popping off the page a little.

It requires two different css properties. box-shadow and transform.

box-shadow creates the shadow. This is controled by 4 values.

box-shadow: ??px ??px ??px #??????;

The first value controls the translation of the shadow on the x-axis 
and the second controls it on the y-axis. The third value controls the
feather of the shadow and the fourth is the color.

transform manipulates and 2D transformations on an element.

For this example, the translate property of transform is used.

transform: translateY(??px);

translate will move the element on one or more of the axes. translateY only translates the
element on the y-axis.

Combine these properties to create the illusion of some object floating!
Use this in combination with the hover effect and you can make an element
pop off the page when the user hovers over it.
