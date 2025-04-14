# Solving-Real-World-Problems-Through-Robotics Objective

In this task I will build a robot that will perform a repetitive, complex, task automatically with little to no need for intervention or control from an operator.

# Purpose of File

Codebase + Readme File - This should be documented appropriately through in-code comments and a readme file. You will use many sources in programming this application. Include references to these sources in the readme file. The readme file needs to also contain instructions to build and use your program including performing each of the tasks mentioned above.

# Instructions to build and use program to perform tasks displayed in video footage

Download and open the repository by:

1. Visiting this link: https://github.com/AbdulRaheemNazir/Solving-Real-World-Problems-Through-Robotics

2. Click the sky blue button that says "<> code"
3. Click the "Download Zip" as the option and a zip file should be found in your downloads
4. Click "Extract all" and modfy to an appropiate directory
5.  Visit this link https://codeexp.vex.com/
6.  Click "File" then "Open" in the browsers IDE
7.  Locate and open the file from the extracted folder "VEXcode Project.exppython"

Adding devices to the IDE by:

1. Click the "Devices" button (located under the "Run" button)
2. Click "+ Add a device"
3. Add the following devices with these settiings and naming conventions

* "motor1" - port 1 - direction is "Reverse"
* "motor2" - port 2 - direction is "Reverse"
* "bumper_start" - port B
* "bumper_stop" - port C

4. Click the "Devices" button to remove the tab
5.  Connect the "Brain" via USB type C to the device you are executing the code
6.  Clcik the "Brain" button and click "Connect"
7.  A modal will pop up saying "Your browser will now attempt to connect to your EXP Controller."
8.  Click "Continue"
9.  2 options are displayed with the numbers "15" and "16"
10. Click "16" and clcik "Connect"
11. Now the "Brain" button should be highighted green

Running the Application:

1. Make sure that the Brain is charged and powered on
2. In the code line 241 and 242 by commenting the line you dont want you trigger the other mode
E.g. the default code will run in "kicking_mode" as "punching_mode" is commented out.
4. Assuming all hardware is setup as desrcibed in the video with the pads at default head positions
8. Click "Run"

# And now it should run just as demonstrated in the video!


## References

- YouTube Tutorial:
  Video provided a foundational inspiration for this project. (https://www.youtube.com/watch?v=o9sAE0G2eaI)
  Specifically RXT-1 Sparring Robot that doesnt make the opponenet just a regular pad but a real time opponent.

- Amazon:
  Articles explaining Depth-First Search (DFS) and Breadth-First Search (BFS), which were used in the maze mapping and pathfinding strategies.  
  - Inspired by shock absorbers from a furniture piece to create our own custom shock absorber (https://www.amazon.co.uk/Housoutil-Absorber-Conditioner-Adjustable-Furniture/dp/B0DQXNZ9P1)  

## Additional References

- Microsoft Copilot during debugging and code refinement.
- Chat GPT O3 Model for commenting code to a level of a non technical person to enhance clarity and adapatability of the code.
- Chat GPT 04 was also responsible for generating a promt for the AI intergration.
- VEX Robotics Community for their resources and tutorials
- Online Resources such as Stack Overflow and GeeksforGeeks
