Launch robot on gazebo
```
ros2 launch articubot_one launch_sim.launch.py 
 ```
Launch Slam
```
ros2 launch articubot_one online_async_launch.py
```
Launch Navigation
```
ros2 launch articubot_one navigation_launch.py
```

# CHANGE WORLD MODEL PATH !!!
open plant_ground_big.world file under that path and change path with yours which is start "<uri>file:///"
/src/articubot_one/worlds/plant_ground/plant_ground_big.world
