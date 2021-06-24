# Instructions: Barrett-Hand-simulation-on-Ubuntu-14-with-Gazebo2

### Platform requirments: Linux system(Ubuntu 14.04 LTS-Indigo), ROS1   
### Hardware requiements: RAM >2GB Memory space: >16GB  
### Graphic card requirments: No  
### Barrett Hand version: BH8-28  
<br/>
<br/>
<br/>
Step 1: install Ubuntu14.04 LTS-Indigo system in your PC. [Instructions Link-Official](https://ubuntu.com/tutorials/create-a-usb-stick-on-ubuntu#1-overview)    
<br/>
<br/>
Step 2: install ROS1(In Ubuntu14.04, you should install **ROS Kinetic Version**). [Instructions Link-Official](http://wiki.ros.org/ROS/Installation)
<br/>
<br/>
Step 3: Creating a workspace for catkin. [Instructions Link-Official](http://wiki.ros.org/catkin/Tutorials/create_a_workspace)
<br/>
<br/>
Step 4 (Optional): Drivers Installing. (If the terminal reports some mistakes on your screen, install related package based on the notifiction)
<br/>
<br/>
Step 5: Install Gazebo [Instructions Link-Official](http://gazebosim.org/tutorials?tut=install_ubuntu)
<br/>
<br/>
Step 6: Download Barrett_Hand_packeges from github  
<br/>  
(1).Enter your ~/src catalog through terminal, then input "git clone https://github.com/gaolongsen/barrett_hand_common"<br/>   
(2).Input "git clone https://github.com/gaolongsen/barrett_hand_sim"<br/>  
(3).Back to your ~/catkin_ws catalog torough terminal, then input "catkin_make" to compile the whole project in this catlog(this command will create cmake file)<br/>
(4).After compile the whole catalog successfully, input". devel/setup.bash"<br/>
<br/>
<br/>
Step 7: Run Simulation: input "roslaunch barrett_hand_gazebo barrett_hand.launch"


