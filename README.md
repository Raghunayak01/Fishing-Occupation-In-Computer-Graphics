## Computer Graphics

Early Graphics System Used for general purpose computers with the standard Von Neumann architecture. Such computers are characterized by the single processing unit that processes a single instruction at a time.
There are different types of Graphics architectures which are:

    •	Display processors: The earliest attempts to build special purpose graphics system were concerned primarily with relieving the general purpose computer from the task of refreshing the display continuously. These display processors had conventional architecture but included instructions to display primitives on the CRT.
    
    •	Pipeline Architectures: The availability of inexpensive solid state memory led to the universality of raster display. For computer graphics application, the most important use of custom VLSI circuits has been in creating pipeline Architectures.
    
    •	The graphics Pipeline: Each object comprises a set of graphical primitives. Each primitive comprises set of vertices.
    
    •	Vertex processing: The assignment of vertex colors can as simple as program specifying a color or as complex as computation of a color from a physically realistic lightning model that incorporates the surface properties of the object and the characteristic light sources in the scene.
    
    •	Clipping and primitive assembly: We must do clipping because of the limitations of that no imaging system can see the whole world at once. The human retina has a limited size corresponding to an approximately 90-degree field of view.

## OpenGL:

OpenGL is strictly defined as “a software interface to graphics hardware” In essence; it is a 3D graphics and modelling library that is highly portable and very fast. Using OpenGL, you can create elegant and beautiful 3D and 2D graphics with exceptional visual quality. The Greatest advantage to using OpenGL is that it is orders of magnitude faster than a ray tracer or software rendering engine. OpenGL is intended for use with computer hardware that is designed and optimized for the display and manipulation of 3D graphics.         
The interface between an application program and a graphics system can be specified through a set of functions that resides in a graphics library. These specifications are called the application programmer’s interface (API). The application program sees only the API and is thus shielded from the details of the both softer and hardware implementation of the graphics library. The software drivers are responsible for interpreting the output of API and converting these data to a form that is understood by the particular hardware. From the perspective of the application program, the functions available through the API should match the conceptual model that the user wishes to employ to specify images

## About Project 

The mini project is about “Fishing Occupation”. A fisherman is supposed to search for the fishes and catch them with the net. After catching the fishes he reaches the market only with the fishes. The boat could be initiated, stopped and made to move at a faster pace while the boat is in motion using the keyboard keys and the mouse button to quit. Thereby the fisherman reaches the bank of the river in display 4 function. In addition to this an option is provided to go back in the reverse direction in the third display. We have used the inbuilt as well as the user defined functions to make the project work. 
The scenario of travelling from one bank of the river to the other side of the river is depicted using Microsoft visual studio application. The project has been designed using visual C++ as language with OpenGL API. 

## SYSTEM REQUIREMENTS

Requirements analysis is critical for project development. Requirements must be documented, actionable, measurable, testable and defined to a level of detail sufficient for system design. Requirements can be  architectural,  structural,  behavioural,  functional, and  non-functional. A software requirements specification (SRS) is a comprehensive description of the intended purpose and the environment for software under development.

##	Hardware Requirement 
      •	Minimum of 2GB of main memory
      •	Minimum of 3GB of storage
      •	Keyboard
      •	Mouse
      •	Display Unit
      •	Dual-Core or AMD with minimum of 1.5GHz speed	

      
## Software Requirement
    •	Windows – XP/7/8
    •	Microsoft Visual Studio C/C++ 7.0 and above versions
    •	OpenGL Files
    •	DirectX 8.0 and above versions
    
## Header Files

•	glut.h

    Object File Libraries
    
•	glut32.lib

    DLL files
    
•	glut32.dll



## User Input:

   ## Control
   
	Press ‘f’ for moving at a faster pace.

	Press ‘q’ to quit.

	Press‘s’ to stop the boat.

	Press‘t’ to start the boat.

	Press ‘n’ to apply the net.

	Press ‘r’ to go in reverse direction.

	Press ‘c’ to move the fishes.

## Mouse Input

	Left mouse button to quit.



## OUTPUT/SCREENSHOTS

Initial Display screen 
![1](https://github.com/user-attachments/assets/62f24084-df3e-4465-9d59-e86daaebb07f)
  Fig 1: The above output shows the initial display screen wherein the fisherman seated on the boat is yet to start moving from the bank. 




Snapshot of the man moving forward
![2](https://github.com/user-attachments/assets/727890d0-de34-4571-8a42-ad238195fbcc)
Fig 2: The above output shows the boat moving with the fisherman in the display1. 
        Key ‘t’ is used for starting the boat and key‘s’ for stopping the boat. 


        
Snapshot when he doesn’t find any fishes
 ![3](https://github.com/user-attachments/assets/d53550dd-86c5-4c5e-ade0-96e6834f72ce)
 Fig 3: The above output shows that the fisherman doesn’t find any fishes. Key ’s’ is	used to stop the boat .Key ‘f’ is used to increase the speed of the boat. 

 
Snapshot in which the man finds the fishes 
![4](https://github.com/user-attachments/assets/c5e7e6b5-81a7-43d0-925f-9b13ad5e099d)
Fig 4: The output shows the boat moving in the forward direction and the presence of fishes.


Snapshot in which the man is moving along with   the net and fishes  
![5](https://github.com/user-attachments/assets/83879b89-ed48-4618-b51b-309103c06820)
Fig 5: The above output shows the fisherman is moving along with the net to the market .Key ‘t’ is used to start the boat and move forward.

Snapshot in which the man applies the net 
![6](https://github.com/user-attachments/assets/d904241b-058f-462b-9aeb-3b4dbacc57e3)
 Fig 6: The above output shows the fisherman applying net on the fishes after finding them .
                    Key ‘s’ is used to stop the boat and then apply the net.  

Snapshot when the man reaches bank with fishes in front of 	the market   		
![7](https://github.com/user-attachments/assets/1460ec2a-771f-4a77-996d-bfea38c0dab3)
Fig 7: The above output shows that the man has reached the destination along with the fishes .He has reached the market in display4. 


Snapshot of the man moving in reverse direction 
![8](https://github.com/user-attachments/assets/384e2ad9-2d83-4ff4-ba5f-60f9d299a071)
Fig 6.8: The above output shows that the boat can move in reverse direction. Key ‘r’ is used to move the boat in reverse direction.

