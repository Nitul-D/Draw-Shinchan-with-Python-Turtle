# Draw-Shinchan-with-Python-Turtle
Drawing Shinchan using python turtle.

Here, we will be learning to draw the famous cartoon character Shinchan with Python Turtle. By the end of this, you will have cleared your concept regarding the basics of python, the basics of the turtle module, and the intermediate of the turtle module. <br />

# Packages:<b />
<b>Import Turtle</b> <br />

# Here, we will see how to code our cartoon and see the code itself. Explanation: <br />
 
<b>First Part:</b> <br />

First, import everything from the turtle module. Then, set a turtle screen into a variable “wn”. Set the screen size to (1000, 700) and the speed to 5. Define a function myPosition() with the parameters “x, y”. Here, pick the penup() as we are not ready to draw. Go to the position as in (x, y). Put the pendown(). Set the pen size to 2. <br />

<b>Second Part:</b> <br />

 Define a function named short() for the shorts of our drawing. Here, set the fill color as ‘#ffec40’. Begin the fill. Now, move the turtle right at 25 units, forward at 20, right at 45, and again forward at 20 units. Move the turtle left at a value of 70 units and again forward at 90 units. Likewise, move the turtle left at 95 units, forward at 90, left at 95, forward at 75, left 85, and again forward at 175 units. Similarly, move it left at 85 units, forward at 75, and as in the code and so on. End the fill. Define another function named leftLeg(). Here, set the position to (-39, -25). Set the fill color as ‘#ffd699’. Begin the fill. Move the turtle right at 89 degrees, forward at 25, right at 90, and forward at 50. Likewise, move the turtle right at 90 units, forward at 20, right at 85, and again forward at 50 units. End the fill. Define other functions for different body parts and you can see that the most used functions and methods are forward, left, right, begin_fill(), fillcolor(), and end_fill().<br />

<b>Third Part (Assemble the parts):</b> <br />

Going on with defining and implying all the function, now, create another one named allLegs(). Inside this function, call all the functions that are associated with drawing the parts of the legs of the cartoon. The functions are : leftLeg(), leftSock(), leftShoe(), rightLeg(), rightSock(), rightShoe(). Likewise, create a function named allHands that assembles the parts of the hands of the cartoon. The functions are: rightHand(), leftHand(), myBis() and leftHand2(). Similarly, create another function named allEyebrows(). Here, call the myEyebrow() function with the arguments (-8, 300), right at 90 units, again myEyebrow with the arguments (72, 300), myEyelid() with the arguments (-8, 270), left with 15 units, and at last myEyelid() with (68, 265). Now, create a function allEyes() and assemble myallEyes1(17, 275) and myallEyes2(95, 270). <br />
 
<b>Last Part:</b> <br />

Here, call all the functions that were assembled in the above part. Here call the function: short(), allLegs(), myShirt(), myHead() ,allHands(), myMouth(), allEyebrows(), allEyes(), myRobot(). After it is done, hide the turtle with the method ht() and finish the code with the done() method.<br />


