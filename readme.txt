/*
Abhishek kumar
201101185
*/
------------------------------------
CSE251: Graphics - Spring 2013:     |
Assignment 2: Moving in a 3D World  |
------------------------------------

How to run:
-----------

-> The makefile compiles the code. (Type 'make' on the terminal)

-> To run:
	> type "optirun ./graphics" (on terminal) to run the executable.
		
		NOTE: without optirun colors might not show up correctly ( i.e. everything will be in black color) or tiles may seem to cross 			      each other.
controls
--------
i/I: turn on/off the spolight
v : toggle viewing node ( FIRST person , TOWER mode , third person, tile view, helicoptermode).
s : respawn the humanoid ( after it has fallen down).
r : rotate the humanoid rightwards slowly ( only in first/third-person mode).
l : rotate the humanoid leftwards slowly ( only in first/third-person mode).
>/. : increase camera pitch in helicopter view mode.
</, : decrease camera pitch in helicopter view mode.
{w/s/a/d}: select different tile in tileview mode, move camera in helicoptr mode.

	Arrowkeys:
	---------
		first-person mode/thirdperson mode				tower-mode/helicoptermode	
	
	up:     move in forward dirn(dirn which is being faced)	|	move into the screen(in -ve z)
	down:	move opposite to the dirn being faced		|	move away from screen, towards us (+ve z)
	right:  turn right(by 90  deg)				|	move in right dirn
	left:	turn left(by 90 deg)				|	move in left dirn


			
	

tiles:
-----
static
moving
missing

stepping on missing tiles or outside the board, will cause the humanoid to fall down. It can be respwaned using 's' key.





