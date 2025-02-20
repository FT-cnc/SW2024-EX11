# Exercise 11
Let's see how we can apply mirror from feature (not from the sketch) for a drawing below 
![](https://github.com/ft-cnc/SW2024-EX11/blob/main/image1.png)</br>

There are couple sketches needed to build this model, one of them would be like below for extrude-boss
1. First we should define the circle A, then draw a diagonal line down B that connected to vertical line C.
2. Secondly we will mirror line B and C.
3. Thirdly, would be connecting line C and C' with line E
4. and finally we can connect line B and B' with line D through "Tangent Arc", ensure the center point of Arc D and center point of Circle A are set to conincident
![](https://github.com/ft-cnc/SW2024-EX11/blob/main/image2.png)</br>

The next skecth would be related extrude-cut, we can use below technique like below
![](https://github.com/ft-cnc/SW2024-EX11/blob/main/image3.png)</br>
1. First we can draw line A downward starting from the vertex inherited from curve D from sketch earlier above down to the base of the extrude-cut area.
2. Second, we can draw line B horizontally up to somewhere below the circle (don't worry about the precise length for now)
3. Thirdly, we can start to draw arc C with "Centerpoint Arc". First point the arc at the same point where the center of the circle located and move the mouse downward to less than a half circle.
![](https://github.com/ft-cnc/SW2024-EX11/blob/main/image4.png)</br>
4. Now, we can start to draw line D vertically up and mirror it to have its twin, line E. Please minimize the mirror for now as we would experiment with mirror feature than mirror sketch.
5. Set the distance between line D and E according to the drawing (.5 inches)
6. Snap the edge of line D to the edge of Arc C. Please note than line D has to be vertically up and Arc C shall be concentric with circle A from previous  sketch.
