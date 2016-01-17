Control 9398 LEGO Car Using Blockly                                        |
===================================                                        |
This document was written by Nadav Yahav and Asher Yanai from the RBD lab, | 
Computer Science Department of the University of Haifa.                    |
                                                                           |
Guided by Dr.Dan Feldman.                                                  |
---------------------------------------------------------------------------


What Is This?
-------------
This is a continuation project of our work which was documented here: http://yahavv.wix.com/reverse-engineering.
In this project we combined number of projects together in order to control LEGO car through Blockly blocks.
Blockly is web-based visual programming editor. This application let anyone controlling the robot car in a simple way.


required software
-----------------
1.Visual Studio 2013
2.Python 3.x
3.Python serial port
4.Djungo server
5.Arduino Development Environment
6.boost_1_57_0 C++ library


Required Hardware 
-----------------
Arduino Uno etc
Lego Car


How To Run The Project
-----------------------
1. Unpack “einav.zip” file at c:\ directory.
2. Locate boost_1_57_0 library at C:\einav\lab\src.
3. Upload “car-code-arduino.ino” in the Arduino envirement.
4. Open command line and run -  C:\einav\blocklygood\mysite3> python manage.py runserver
5. Open web browser in this link  - localhost:8000/static/blockly/tests/playground.html
6. Run server.exe
7. Open Robots.sln Visual Studio project and run CarController solution as StartUp Project.
8. Go to the playground.html, drag the requested block and click on the “execute on server” button. 


How To Create Your Own Block
----------------------------
1. Go to C:\einav\blocklygood\mysite3\polls\static\blockly\generators for setting your own block logic.
2. Go to C:\einav\blocklygood\mysite3\polls\static\blockly\blocks to design your own block view on the webpage.
3. Change playground.html  to fit your new block
4. Open C:\einav\blocklygood\mysite3\polls\views.py file to determine the server logic.

More Info
---------
RBD lab webpage -	http://sites.hevra.haifa.ac.il/bdrl/
Our site  - 		project work site - http://yahavv.wix.com/reverse-engineering
Videos - 		https://youtu.be/GVIHn-xUwrw

			https://youtu.be/DVDlOkhHr1s
Credits
-------
1. “Robots” project was developed by David Dorfman.
2. Our project was based on previous Blockly project (for lady bird) which was developed by Oren Tvila and Yuval Brave.
