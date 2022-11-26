# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.
### Program:
![k7 2](https://user-images.githubusercontent.com/94296221/204073486-3de8f5b8-e6e5-478b-b605-4e7af23ceebf.png)
![k7 3](https://user-images.githubusercontent.com/94296221/204073488-2b51c6ad-2866-413b-874f-46d9e1dad310.png)
![k7 4](https://user-images.githubusercontent.com/94296221/204073489-2c283d80-84a8-48d5-a4ab-8142f72b41e6.png)

![k7 5](https://user-images.githubusercontent.com/94296221/204073492-47600474-8e07-4ca9-bc05-f3545dcca036.png)

### Linear Interpolation

![k7 6](https://user-images.githubusercontent.com/94296221/204073494-a7c7912c-a881-410b-b67a-81a7ec867091.png)







### Circular Interpolation
![k7 7](https://user-images.githubusercontent.com/94296221/204073499-820e77b9-d886-479e-a6ca-753592842aba.png)

### output
![k7 8](https://user-images.githubusercontent.com/94296221/204073503-d744d3a9-a07c-4465-a4f8-45b03ce78058.png)
![k7 9](https://user-images.githubusercontent.com/94296221/204073587-5a82e775-5d3d-46fd-9d62-e1b5ebc58419.png)


### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.


 
