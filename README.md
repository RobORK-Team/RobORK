RobORK
======

In the pre-proposals, Mustafa’s robot was a ball boy and Doğan’s robot was for erranding. Both of the robots were capable of holding/grabbing objects and transport the object somewhere. Thus, after combining these ideas, we decided on a goalkeeper-like robot.
	The robot will be programmed for the environment in the picture below. A goal post, three walls and football lines. There will be three modes for the robot.


1-Penalty Kick Mode
	In the Penalty Kick Mode, initially the ball will be in penalty point. By a terminal command user will give a velocity to the ball object. The robot will try to block the goal. After that, the robot will hold the ball and transport the ball to the penalty kick point.
	
2- Erranding Mode

In this mode, robot will take ball from somewhere on pitch and put it down on pitch where user wants. 

3- Free-kick Mode

Robot will keep the ball which user sends from corner of pitch. It’s difference from the Penalty Kick Mode by the torque factor.

	As the platform we will use Gazebo and we will work on PR2. We will use camera sensors of the robot and identify the ball position. For the Free-kick and Penalty Modes,  the robot will position in front of the goal line. It will block the ball with its body or raise its hands to block. To perform this, it estimates the ball’s route.
	Initially, the robot knows the pitch area. Thus, it will be easy to put the ball on a selected point. As you see, the robot is totally perfect for the football pitch both as a goalkeeper and as a errander. 
