# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 

## Program:
![image](https://user-images.githubusercontent.com/75235167/206196691-372cae70-bac0-4f6c-aee0-9d4874964aeb.png)
![image](https://user-images.githubusercontent.com/75235167/206196760-bca4954a-3b7a-4419-b4a6-e727cc68d113.png)
![image](https://user-images.githubusercontent.com/75235167/206196835-ea000c38-34c4-4111-812d-2d38b5bb70b9.png)
![image](https://user-images.githubusercontent.com/75235167/206196892-4c320441-7727-40b9-b4d2-4085e0135d90.png)
![image](https://user-images.githubusercontent.com/75235167/206196953-ce0069d7-1672-4fcd-a57a-3223f058dffe.png)

### Linear Interpolation
![image](https://user-images.githubusercontent.com/75235167/206197040-c8ffe16b-1e44-45b1-a856-22efd029dba7.png)

### Circular Interpolation
![image](https://user-images.githubusercontent.com/75235167/206197149-dfc83880-3744-434d-97eb-531d495860e5.png)

## output
### Linear Interpolation:
![image](https://user-images.githubusercontent.com/75235167/206197237-92b1f7c7-e929-4bcf-85be-a34dff7eca68.png)

### Circular Interpolation:
![image](https://user-images.githubusercontent.com/75235167/206197402-fa5ee1ea-2169-4ec7-9b9d-edaa1a9cc938.png)

### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.


 
