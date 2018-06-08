# teleop

Teleop example using joystick.

Works for Microsoft Xbox 360 Wired joystick or compatible, like Logitech F310 (used in XInput Mode).

## Installation

Install ros_examples package if not yet done.

Install joystick driver.
```
sudo apt-get install ros-kinetic-joy
sudo chmod a+rw /dev/input/js*
```
Your joystick will be any of the js devices in /dev/input directory. i.e. /dev/input/js0 or /dev/input/js1.

Install joy_teleop package:
```
sudo apt-get install ros-kinetic-joy-teleop
```

## Launch

launch teleop example as follows:
```
roslaunch teleop teleop.launch
```

## References

- http://wiki.ros.org/joy
- http://wiki.ros.org/joy/Tutorials/ConfiguringALinuxJoystick
- http://wiki.ros.org/joy_teleop
