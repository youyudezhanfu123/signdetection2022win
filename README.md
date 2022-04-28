# signdetection2022win
# Things you need to set up the environment: Camera Drive ( avt_vimba_camera ), fully installed ROS command environment, vimba, Asus router (if you want to config the camera while using wifi, wifi is not necessary), etc/network/interface (if you want to set individual static IP for camera)
# Please follow the instruction I included. There are image records to help you through it. 
# Our team's code are in the Jetson_Xavier's folder on desktop name as ros_workspace. I have merged my files (from original catkin_ws folder) to this so you can work with the camera and also connect to detectnet. Due to the root permisson issue I was not able to upload all the files but they are in this workspace and you can just launch it from there. 
# command to launch: inside ros_workspace directory
catkin_make
source devel/setup.bash
rosrun image_view image_view ip:=10.42.1.35  //This is if you want to see the raw image from the camera.
 
