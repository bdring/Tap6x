# Tap6x

![](https://github.com/bdring/Tap6x/blob/master/docs/images/20190919_094658.jpg)

This is a demonstration and test platform for 6 axis CNC control. It is basically 2, 3 axis machines nested together. One uses X,Y and Z axes and the other uses A,B and C axes. For reference I will refer to them as machine #1 (XYZ) and machine #2 (ABC), but it is important to know this is really one machine, with one controller.

Machine #1 and #2 can be coordinated using move commands that reference axes from both machines, such as G0X10B10. You can move only one machine by just referencing its axes, like G0X5Y10. You **cannot** independently control both machines at the same time. For example, you cannot move in a box shape on 1 machine and a circle shape on the other using normal  gcode. You could fake it by drawing that circle with 100 little line segments and breaking the box shape into 100 segments as well.

[Here is a link to a video of the machine.](https://www.youtube.com/watch?v=RVi9n5H70DY)

[Here is a link to an interactive 3D model](https://workbench.grabcad.com/workbench/projects/gcf_8U3VLbOsAYxRylXoI0eItX2JMccR723CNI4EUbWPf5#/space/gcU0tkRxl2ZquH66L1B1xCTAAVmUapjxbL5vyWsJLSwVSN/link/2013338)

### Donation

This project represents a lot of work. Please consider a safe, secure and highly appreciated donation via the PayPal link below.

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TKNJ9Z775VXB2)
