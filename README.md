# Tap6x
This is a demonstration and test platform for 6 axis CNC control. It is basically 2, 3 axis machines nested together. One uses X,Y and Z axes and the other uses A,B and C axes. For reference I will refer to them as machine #1 (XYZ) and machine #2 (ABC), but it is important to know this is really one machine, with one controller.

Machine #1 and #2 can be coordinated using move commands that reference axes from both machines, such as G0X10B10. You can move only one machine by just referencing its axes, like G0X5Y10. You **cannot** independently control both machines at the same time. For example, you cannot move in a box shape on 1 machine and a circle shape on the other using normal  gcode. You could fake it by drawing that circle with 100 little line segments and breaking the box shape into 100 segments as well.

[Here is a link to a video of the machine.](https://www.youtube.com/watch?v=RVi9n5H70DY)