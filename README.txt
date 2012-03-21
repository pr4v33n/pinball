Program Executable: BallBreaker.jar
Program Sourcecode: BallBreaker.java
Author            : Praveen Kumar Telugu
Email             : tpk1024@gmail.com

It's a rudimentary version which offers the minimal features of the reference
ball breaker game (Flash one).

The following Keys can be used:

<Left-Arrow>     ------ Moves the player block to the left
<Right-Arrow>    ------ Moves the player block to the right
<SPACE>          ------ Pause/Resume the game (If one is running)
<Y>              ------ Start a new game (If none is running)
<R>              ------ Reset top scores (When shown on screen)

Score and Lives remaining info is displayed in the bottom of the frame.

Now shows top scores at the end of the game (Keeps track of them across sessions!)
Brick layout changed as specified.
Audio support added.
Conditions for the audio to work:
 - The file "impact.wav" should be present in the same folder as the jar
If any of the above condition fail the program disables the audio itself and runs as usual (ie. no sound version)

Command to invoke: "java -jar BallBreaker.jar"
On windows double clicking the jar may be enough to start the game.

Test environment: Developed and tested on ArchLinux and Java 6 SE
