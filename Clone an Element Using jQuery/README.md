In addition to moving elements, you can also copy them from one place to another.

jQuery has a function called clone() that makes a copy of an element.

For example, if we wanted to copy target2 from our left-well to our right-well, we would use:

$("#target2").clone().appendTo("#right-well");
Did you notice this involves sticking two jQuery functions together? This is called function chaining and it's a convenient way to get things done with jQuery.

Clone your target5 element and append it to your left-well.

Tests
Your target5 element should be inside your right-well.
A copy of your target5 element should also be inside your left-well.
You should only use jQuery to move these elements.