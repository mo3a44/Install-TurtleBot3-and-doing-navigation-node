# Install-TurtleBot3-and-doing-navigation-node



first 
Install TurtleBot3 Packages

Install TurtleBot3 via Debian Packages.

```
$ sudo apt-get install ros-kinetic-dynamixel-sdk
$ sudo apt-get install ros-kinetic-turtlebot3-msgs
$ sudo apt-get install ros-kinetic-turtlebot3
```


second name the model  for example i will use burger 


```

export TURTLEBOT3_MODEL=burger

```

now we will open the the Navigation Simulation using this command line 

```

$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

```

