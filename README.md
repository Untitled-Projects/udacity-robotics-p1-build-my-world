Udacity Robotics Software Engineer Nanodegree 
Project 1 Build My World by Michael Strobl

The following is included:
- Gazebo building with 1 floor (model/mybuilding)
- 1 Robot inserted two times (model/myrobot)
- Additional resources from the Gazebo Online Library 
- C++ Plugin Script with the message: 'Hello to Michael's World'

To start the code:
```
$ mkdir build
$ cd build/
$ cmake ../
$ make 
$ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/myrobot/build
```
