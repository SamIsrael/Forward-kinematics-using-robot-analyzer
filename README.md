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
#### Name     : Sam Israel D
#### Reg.No   : 212222230128
```
1. Open the roboanalyzer software.
2. Select the robot and its degrees of freedom.
3. Change the values with the link lenght wherever necessary. 
4. Simulate the model for forward kinematics. 
5. Plot the graph between the link and the joints. 
6. Update the DH parameters of the link configuration and end effector configuration.
```




### SIMULATION 
 #### 4 DOF:
 ![Screenshot (406)](https://github.com/SamIsrael/Forward-kinematics-using-robot-analyzer/assets/118707037/0141c7e2-e0bb-4d0b-ad7b-51b67ab596f2)
 #### 6 DOF:
 ![Screenshot (407)](https://github.com/SamIsrael/Forward-kinematics-using-robot-analyzer/assets/118707037/09f8483c-d687-43b1-acfe-44d816c4532e)

 
 
 
 
 
 ### PLOT 
  #### 4 DOF:
  ![Screenshot (405)](https://github.com/SamIsrael/Forward-kinematics-using-robot-analyzer/assets/118707037/d7bdc228-7deb-4602-9896-6a0af3e2ffe5)
  
  
  ![Screenshot 2023-05-19 112003](https://github.com/SamIsrael/Forward-kinematics-using-robot-analyzer/assets/118707037/7b8036ce-4c19-46f6-bfc5-a6271231a96a)
  
  #### 6 DOF:
  ![Screenshot (408)](https://github.com/SamIsrael/Forward-kinematics-using-robot-analyzer/assets/118707037/4e2407c0-5724-4aee-80f2-6adda6f4faca)
  
  
  ![image](https://github.com/SamIsrael/Forward-kinematics-using-robot-analyzer/assets/118707037/fafc3edf-8d0e-47f8-bc45-0313b250e7d3)

 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
