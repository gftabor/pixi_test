# pixi_test


```
pixi shell


colcon build --symlink-install --event-handlers desktop_notification- --event-handlers console_cohesion+ --cmake-args -DBUILD_TESTING=OFF --packages-skip ros2_control


call install\setup.bat
set GZ_SIM_SYSTEM_PLUGIN_PATH=%cd%\install\gz_ros2_control\bin

ros2 launch gz_ros2_control_demos cart_example_velocity.launch.py

```

Second terminal

```
pixi shell
ros2 run gz_ros2_control_demos example_position
```
