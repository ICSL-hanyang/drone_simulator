copy pkg in catkin_ws/src & cm

sudo apt-get install ros-kinetic-urdf,kdl_parser,robot_state_publisher,collada_urdf
sudo apt-get install ros-kinetic-joint-state-controller,effort-controllers,position-controllers
  while(1){
  trajectory_msgs::MultiDOFJointTrajectory trajectory_msg;
  trajectory_pub.publish(trajectory_msg);
  }
binding by while(1)
# drone_simulator