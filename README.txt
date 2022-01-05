# OOP_Project_Spring_Friction_Forces
This project is done as a part of Object Oriented Programming course (CSF213) SEM-1, 2021-22. The title of the project is Spring, Friction and Forces
/*
Project: 2. Spring Friction and Forces
Group No: 26
Name: 	Sudhanshu Mishra, 2019B1A70750P
	      Satyam Srivastava, 2019B1A70188P	
*
------------------------------------<<Execution Document>>---------------------------------------------------------
To run the Application, run the jar executable file "2_2019B1A70750P_2019B1A70188P_ExecutableFile" in the command prompt using the command-
	"java -jar 2_2019B1A70750P_2019B1A70188P_ExecutableFile.jar"

Assumptions-
	1) N is either 1 or 2. Scope of the project is limited and mentioned in the Evaluation_Document file.
	2) The rollable objects are always in pure rolling motion, no sliding ever takes place.
	3) Friction coefficient between two objects and between the ground and object is considered to be same.
	4) Specific configurations of shapes for simulations are only allowed.
	5) The order for the input needs to be maintained.
	6) Object rolling on the top of the box never falls off in the time duration of the simulation.

To execute the application-
	1) Run the Driver class and enter the inputs asked in the console window. 
	2) Output for the simulation gets stored in the output.csv File.
	
Shapes available
	1. BOX
	2. BALL
	3. RING
	4. CYLINDER

Simulation Configurations available
	1. Box on Ground
	2. Box on Box
	3. Ball on Ground
	4. Ball on Box
	5. Ring on Ground
	6. Ring on Box
	7. Cylinder on Ground

* Spring Box system configuration is not considered in the application because of the variable acceleration requiring maths libraries, to keep the mathematical part simple. 
* Slope is not considered to reduce the physical complexity of the application and keep the scope of the project bound.
* Cylinder on ground is same as Ring on Ground. So, it is not included so as to avoid redundancy.

-----------------------------------------------<<TEST CASES>>-----------------------------------------------------------------------------------------

INPUT FORMAT
N
g
mu
no of snapshots
time slice

<<Enter details of N shapes>>
shape ID
mass
orientation
x-coordinate
y-coordinate
velocity
shape specific arguements

TESTCASE 1
1
10
0.02
5
0.2
1
10
0
4
0
6.5
3
3

TESTCASE 2
2
10
0.03
8
0.1
1
10
0
0
0
12
3
7
1
5
0
0
0
7
3
3

TESTCASE 3
1
9.8
0.05
6
0.3
2
5
0
0
0
7.8
5

TESTCASE 4
2
9.8
0.2
4
0.1
1
7
0
3
0
12
2
15
2
6
3
2
15
3

TESTCASE 5
1
10
0.03
10
0.3
3
6
0
5
0
4
7

TESTCASE 6
2
9.8
0.2
6
0.1
1
8
0
6
0
13
3
20
3
2
0
6
3
9
3

TESTCASE 7
1
9.8
0.5
8
0.2
4
16
0
3
0
10
15
6

TESTCASE 8 (INVALID)
0
This is invalid test case because scope of project is limited either to 1 or 2 shapes.

TESTCASE 9 (INVALID)
4

TESTCASE 10 (INVALID)
2
10
0.2
5
0.1
3
This is invalid test case because lower shape can not be ring in 2 shape system.


