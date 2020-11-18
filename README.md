# A-Web-Page-of-Calculator-Using-HTML-CSS





1. Start and Go to Code Pen.
2. we are going to create a calculator. We need to create a basic structure
using HTML, style it using CSS and make it work using JavaScript.
3. I created the div (.box) which represent the structure of calculator. Inside it, I
created two div tags, one for display (inside this, I added input type="text" to
display the result and set this to read only) and one for Keys.
4. I set background color for body and set the height, width and border
radius of class box (.box).
5. I set .display background-color, width, height and position. Inside it, we have
an input box, I also adjust its height, width, color, backgroundcolor and position.
6. I adjust position of div (.keys). I use Double Class Selector(
example: class=button gray). By the use of this, I set .button
width, height, border-radius, cursor, etc. This helps me in making all my
buttons of the same width, height, etc. Then I
set .button.gray color, background-color, etc.
7. After that, I create :active (The :active pseudo selector will match when an
element is being pressed down on by the mouse Cursor.) for buttons. The thing 
I have done here is to change the top border color to black and bottom color to
same as button color. This gives button feel of pressing down.
8. we have created a Calculator but it does not work. Now we have to do
scripting for it (using JavaScript).
9. I have created three functions. Function c(val) is used for clearing the data
from the display. When we click on "C" button, then onclick='c("")' event runs
and searches for c(val) function and displays the value according to the
parameter passed inside it (here, we have not passed any parameter so the
input screen appears blank or clear).
10. Function v(val) is used for typing numbers as well as mathematical
operators.
11. Function e() is used for evaluating, i.e., on clicking "=" button, value inside
the Id="d" is solved.
