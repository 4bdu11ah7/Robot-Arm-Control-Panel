# Robot-Arm-Control-Panel
This is a Control Panel for a Robot Arm,
this project provides a simple web interface to control a 6-motor robot arm.

Users can adjust each motor’s angle using sliders,
save different arm positions ("poses") to a MySQL database, 
load and delete saved poses, 
send the latest pose to the robot arm for execution.

The interface uses HTML, CSS, and JavaScript for the frontend, and PHP with MySQL for backend database handling.

# Features
Control six motors with sliders.

Save, load, and delete saved poses.

Run the latest saved pose on the robot arm.

Dynamic updates without page reloads using Fetch API.

# Setup Instructions
Create a MySQL database named 'robot_arm' 
with a table 'robot_arm_status' to store motor positions and status.

Upload all PHP files to your web server.

Update database connection settings in PHP files if necessary.

Open index.php in your browser and start controlling the robot arm.
