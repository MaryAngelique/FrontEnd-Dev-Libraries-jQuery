Now let's try moving elements from one div to another.

jQuery has a function called appendTo() that allows you to select HTML elements and append them to another element.

For example, if we wanted to move target4 from our right well to our left well, we would use:

$("#target4").appendTo("#left-well");
Move your target2 element from your left-well to your right-well.

Tests
Your target2 element should not be inside your left-well.
Your target2 element should be inside your right-well.
You should only use jQuery to move these elements.