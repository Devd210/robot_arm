# Robot arm

# Installtion   
    1. Install all the dependencies use
    rosdep install --from-paths src --ignore-src -r -y

    2. catkin build robot_arm 
    3. source devel/setup.bash
# RUN
    roslaunch robot_arm robot.launch
    open the robot_arm/script/index.html 
    enter the postion values of the robot's angular and linear displacement of robot's shoulder and arm the submit.