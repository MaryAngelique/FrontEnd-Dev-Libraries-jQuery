When HTML elements are placed one level below another they are called children of that element. For example, the button elements in this challenge with the text #target1, #target2, and #target3 are all children of the <div class="well" id="left-well"> element.

jQuery has a function called children() that allows you to access the children of whichever element you've selected.

Here's an example of how you would use the children() function to give the children of your left-well element the color blue:

$("#left-well").children().css("color", "blue")
Give all the children of your right-well element the color orange.

Tests
All children of #right-well should have orange text.
You should use the children() function to modify these elements.
You should only use jQuery to add these classes to the element.