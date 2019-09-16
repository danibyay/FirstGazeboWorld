# First Gazebo World

----
This project is a custom Gazebo world that has the following features

* A building with walls, doors, and windows.
* A model of a robot with joints
* Models from the gazebo online library
* A C++ Hello World Plugin

----
## usage
- Build
    
`mkdir build && cd build`

`cmake ../`

`make`

`export GAZEBO\_PLUGIN\_PATH="absolute_path_to_build/"`

- Open the world


`gazebo world/smallHospitalWorld &`
