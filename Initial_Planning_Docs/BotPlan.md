Initial Plan is Subjected to change occasionally, without notice

Need to make two Bots

The one that is controlled Manually and
The one that is controlled by AI

Player will have option to choose which bot he wants to play with.

Both the bots will be majorely 3d printed (Easier open source manufacturing for the people).
Both the Bots will be clones but different color scheme (Prevent unfair advantages of wait or extra components).
Both the bots will have Esp32 which connects them to Server Running ROS (Underneath the table).
Both the bots will have a QR code on the top so its easier to capture by the vision system.

Design the bots in such a way so the ball stays easy to steal, keeping matches exciting.
Avoid claws or U-shaped grippers—they trap the ball and slow the action.

Shallow concave bumper	- Front bumper is curved to match the ball but ends before the ball’s mid-line (≤ 60 ° arc).

Server Design:
The Server will have 3 processes parallel to each other.

1st Process:
 Take in Manual Data from users controller and send movement data to the bot.

2nd Process:
 Takes Vision Data(Or some form of feedback from the game), make decision(Path Planning) and send movement data to the bot.

3rd Process:
  There will be a sensor placed in the Posts that will update the Servers Score Board and the server will update the physical Score Board


Piston Mechanism(ON HOLD): - Gonna keep it simple the Piston Mech is on hold the bot can just collide to hit the ball ahead.
there will be a piston type kick mechanism in the centre of the arc so it can hit the ball in the centre.
It will be a spring mech that can be pulled back and realeased, using a small motor.
There will be a sensor to detect if the piston is realeased or back (LimitSwitch)
To make it easier the bot will have in-build local program that will make sure piston is alway loaded and when we 
press the RT button of the controller it kicks and restore back.
