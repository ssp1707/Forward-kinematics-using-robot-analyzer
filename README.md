# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:

1. Open the roboanalyzer software.<br>
2. Select the robot and its degrees of freedom.<br>
3. Change the values with the link lenght wherever necessary.<br>
4. Simulate the model for forward kinematics.<br>
5. Plot the graph between the link and the joints.<br>
6. Update the DH parameters of the link configuration and end effector configuration.<br>

### SIMULATION 
### 4DOF

![2 3](https://user-images.githubusercontent.com/75234965/199652985-4a00c056-c916-4565-947a-bf89571354ac.png)

### 6DOF

![2 1](https://user-images.githubusercontent.com/75234965/199652967-670eb2a9-ddda-4c9f-ba35-53bdc98dd0dd.png)
 
### PLOT 
 ### 4DOF
 
![2 2](https://user-images.githubusercontent.com/75234965/199652405-8273d7cd-499f-41b4-bad4-bd4898c19dc1.PNG)

### 6DOF

![2 4](https://user-images.githubusercontent.com/75234965/199653003-48ba64e4-317b-448b-acda-b6ba1ce198a2.PNG)

### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
