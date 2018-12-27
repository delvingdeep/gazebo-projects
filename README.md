This project is a part of submission for Udacity's Robotics Software Nanodegree project "BUILD MY WORLD"

###### Files included:
- model
    - building
       - mybuilding
         - model.config
         - model.sdf
    - robot
      - myrobot
        - model.config
        - model.sdf
- script
  - welcome_message.cpp
- world
  - deep_world
- CMakeLists.txt
- myrobot.png
- mybuilding.png
- myworld.png


###### Summary:
Before executing the project, a build is required. Execute following steps to build project and run it:

```
$ cd build
$ cmake ../
$ make
```
Above steps builds projects, and is now ready to run using following steps:
```
$ cd ../world/
$ gazebo deep_world
```

###### About Model:

I have made a four wheel drive robot for this project using Gazebo's Model Editor tool

![My Robot]myrobot.png

After that I build my building layout for this project using Gazebo's Building Editor tool

![My Building]mybuilding.png

At last, I imported my model and building to make a Gazebo world using some objects from Gazebo's online library like Cafe Table, Pine Tree, Person, Bookshelf, etc.

![My World]myworld.png
