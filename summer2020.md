# Navigation2 Project tasks for [Summer 2020 Student Program](https://isrc.iscas.ac.cn/summer2020)

### 1. Create a Configuration Assistant Analog to MoveIt

**Task description** 

[Moveit](https://moveit.ros.org/) has long has a QT configuration assistant. MoveIt also has a bunch more auto-generated files required to work and more complex things to describe with kinematic chains than Navigation2 that has made sense.

However, a configuration assistant could be extremely beneficial to Navigation2 developers on their way with minimum friction. We should provide a gui tool to cover the following configurations:

- the broad strokes with the costmap
- configurable costmap layers
- URDF and frame selection to make sure the options comply with standards, planner, and controller
- @steve please add more specific options

After the items are configured, there should be a preview to see how the parameters effect the robot.

**Project difficulty: high**

**Project community mentor: Steve Macenski [@SteveMacenski](https://github.com/SteveMacenski)**

**Mentor contact details: stevenmacenski@gmail.com**

**Contact information for the cooperating mentor (optional):  juzhenatpku@gmail.com**

**Project output requirements**

- A QT based GUI configuration assistant that support the parameters listed above
- A preview panel to display the parameters' effection on the robot

**Skills required**

- C++, QT framework
- JSON/XML parsing
- Gazebo simulation
- 3D programming(maybe needed in the preview)

**List of relevant open source software repositories and refs** 

- [QT](https://www.qt.io/)
- [Gazebo Simulator](http://gazebosim.org/)
- [Original github issue page](https://github.com/ros-planning/navigation2/issues/1721)

