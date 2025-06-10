Initial Plan is Subjected to change occasionally, without notice

Need to make two Bots

The one that is controlled Manually and
The one that is controlled by AI

Both the Bots will be clones (Prevent unfair advantages of wait or extra components)

Both the bots will have Esp32 which connects them to Server Running ROS (Underneath the table)

Design the bots in such a way so the ball stays easy to steal, keeping matches exciting.
Avoid claws or U-shaped grippers—they trap the ball and slow the action.

Shallow concave bumper	- Front bumper is curved to match the ball but ends before the ball’s mid-line (≤ 60 ° arc).
there will be a piston type kick mechanism in the centre of the arc so it can hit the ball in the centre.

Piston Mechanism
It will be a spring mech that can be pulled back and realeased, using a small motor.

There will be a sensor to detect if the piston is realeased or back (LimitSwitch)
To make it easier the robot will have in-build local program that will make sure piston is alway loaded and when we 
press the RT button of the controller it kicks and restore back.

The Server will have 3 processes parallel to each other 

1st Process:
 Take in Manual Data from users controller and send movement data to the robot.

2nd Process:
 Takes Vision Data(Or some form of feedback from the game), make decision(Path Planning) and send movement data to the robot.

3rd Process:
  There will be a sensor placed in the Posts that will update the Servers Score Board and the server will update the physical Score Board
