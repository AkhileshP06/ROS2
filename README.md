
### Robotic Operating Systems & Robot Simulation in ROS2

This repository is a fork from [@NippunKumaar](https://github.com/NippunKumaar/ROS2-Course)'s original repository for the Robotic Operating Systems and Robot Simulations course. It contains code and materials related to the assignments completed during the labs throughout the course.


## Getting Started
Follow the instructions from [ROS2 documentation](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)
to install & setup ```ROS2 humble hawksbill``` & ```gazebo``` on ```Ubuntu 22.04 Jammy Jellyfish``` or any other compatible Linux distro.




## Folder Structure
The project has the following structure:
- build: Contains intermediate build files generated during the compilation process.
- install: Contains installation files and artifacts for ROS2 packages.
- log: Stores log files related to each project.
- src: Contains source code for all assignments completed during the course labs.
## Usage
To try any of the lab assignments follow these steps :

1. Refer [ROS2 documentation](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html) to create & setup a ROS2 workspace.

2. Navigate to the root of your workspace and enter the command ```colcon build``` to build all packages inside the workspace or enter the command ```colcon build --packages-select <my_package>``` to build a specific package

3. To run the executable node in any package enter the command: ```ros2 run <my_package> <my_node>```

 4. To launch a simulation of any model on gazebo enter the command: ```ros2 launch <model_name>_gazebo <world_name>.launch.py```
## Contributing

Contributions are always welcome!

If you would like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them to your branch.
4. Create a pull request.

