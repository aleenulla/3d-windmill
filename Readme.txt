Project Name: Implementation of 3D Windmill 

How to run this Project

1. Open codeblocks or Visual Studio code
For codeblocks:
1. Creating a Project (Each file must be created under opengl project)
	File -> 
	New Project -> 
	GLUT Project -> 
	(C:\Program Files (x86)\CodeBlocks\MinGW)Glut's File Location
	Select GNU GCC Compiler, check create "Debug" configuration and uncheck create "Release" configuration.
2. Select the main file and open in editor that exists under management widget->main.cpp
3. In main file in first line write "#include<windows.h>" **Required in windows os**
4. copy the source code from "source.cpp" file and paste it in main.cpp under the header line
5. Build and run to see the output from the project.
6. Right click on the screen to select options from the menu.

For Visual Studio code:
1. Create an empty file and store it in a folder on Desktop.
2. In program file in first line write "#include<windows.h>" **Required in windows os**
3. copy the source code from "source.cpp" file and paste it in main.cpp under the header line
4. To compile and run the code use terminal. The command to open terminal is (ctrl + ~) or Press Terminal -> New Terminal from MenuBar. [Exclude Round Brackets ( )]
5. Build using the command (gcc -m32 -Wall filename.c -L "C:\MinGW\lib" -lglu32 -lglut32 -lopengl32) in terminal.
6. After Successful Compilation run the command (.\a.exe) [Exclude Round Brackets ( )]
7. Right click on the screen to select options from the menu.