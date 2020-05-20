# RND-Build-My-World-Project
First project of the Robotics Course of Udacity

## Install Gazebo
`$ curl -sSL http://get.gazebosim.org | sh`

## Build project
`$ mkdir build`  
`$ cd build`  
`$ cmake ..`  
`$ make`  
`$ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/RND-Build-My-World-Project/build`
Change `/home/workspace/` for the directory path where the project was cloned.

## Run project
`$ cd ..`  
`$ cd world`  
`$ gazebo myworld`  
