# Linux-and-ROS-based-Robot-Operation
Implemented a robot software system that performs an operation of fulfilling the shipment order and delivering them through an industrial AGV.  
The robot performs the following tasks in order to fulfill the shipment order.  
1.  Reads an order. 
2.  Identify the products (parts) that constitute the order. 
3.  Pick up one of these products from the conveyor belt or storage bin and place it on the AGV tray. 
4. Commands the AGV to deliver the products after the order is completed.


------HOW TO RUN:  -----------------
Follow the instructions :

Extract the package in your workspace and build it using: 

1. catkin_make 
2. source devel/setup.bash

Give permissions to the script named "pick_place.sh" by making your present working directory as the package (need xterm installed to run this, install using "sudo apt-get install xterm") and do: 
	
3. cd /path/to/package/
4. sudo chmod a+x pick_place.sh

Run the packages by running the script: 

5 ./pick_place.sh


Contents:
Folders
   - config
   - include
   - launch
   - src
   - video
   - CMakeLists.txt
   - package.xml
   - pick_place.sh
