# cube_3d_purescript


                                              Desigining of 3D Cube in PureScript
	Firstly, need to install node.js to run purescript commands in pc.The installation process for PureScript is below:
 PURESCRIPT INSTALLATION
 STEP 1 : npm install -g purescript
 STEP 2 : npm install -g pulp bower
To run purescript
STEP 3: pulp init
STEP 4: pulp run
 

STEP 5: pulp server
 

Process:
⦁	Create a file index.html to import the app.js script file .
⦁	While running the command "pulp run" automatically app.js will be creates in output folder.
⦁	Need to add dependencies according to the program
	ex:         	 "purescript-prelude": "^3.1.0",
    "purescript-console": "^3.0.0",
    "purescript-js-timers": "^3.0.0",
    "purescript-jquery": "^4.2.1",
    "purescript-linear-algebra": "^0.4.0",
    "purescript-numbers": "^5.0.0"

⦁	Created a file named as "Matrices.purs" to add cube formations like rotations ,transformations
⦁	This Matrices.purs file  imported in "Main.purs". 	
REFERENCES:
⦁	For the animation and User Interface (UI) purpose used this reference
	https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js
⦁	I refered google to know the cube angles
	ex:-  transform : "translateX(-100px) translateY(-100px) translateZ(-100px)"


 
