Technical Assignment: When the player character spawns, a small robot (which can be replaced with a regular mannequin) also spawns nearby. The robot has the following functions:

In its default state, the robot follows the player character. The robot and player do not collide and can pass through each other.
If the robot is unable to reach the player (e.g., the player jumps onto a large rock), the robot teleports to the player after a few seconds.
Several bananas are scattered across the map. The player can point to a banana (if the player can see it), and the robot will head directly toward it. Once the robot reaches the banana, it attaches it to itself and returns to the player. Upon returning, the robot drops the banana and resumes following the player.
If, while the robot is heading toward a banana, the player points to another banana, the robot switches targets, abandoning the first one. Similarly, if the robot is carrying a banana back to the player and the player points to another banana, the robot drops the current one and heads for the new target.

Demo video: Demo_video
