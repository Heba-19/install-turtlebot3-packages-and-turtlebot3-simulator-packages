# install-turtlebot3-packages-and-turtlebot3-simulator-packages
copy this commands in your src folder in the terminal each line individuall

git clone https://github.com/ROBOTIS-GIT/turtlebot3.git #in src folder
cd .. #back to workspace folder
Catkin_make
cd #src folder name
git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git #in src folder
cd ..
Catkin_make
source devel/setup.bash
export TURTLEBOT3_MODEL=burger 
roslaunch turtlebot3_fake turtlebot3_fake.launch  #to launch rviz simulation
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch # to contrle the mov of robot
don👍!
