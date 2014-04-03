lab2
====
* To install do:
* cd ~/catkin_ws/src/
* git clone https://github.com/aliunwala/lab2.git
* cd ~/catkin_ws/
* catkin_make


* To run do:
* plug in a kinect                       // To both the wall jack and the computer. Alternatively just use one of the segbots.
* roslaunch openni_launch openni.launch  // starts publishing kinect data
* rosrun lab2 kinect_print_to_screen     // takes the weirdness of PointCloud2 and publishes an PointXYZ instead. Which is much easier to reason about.
