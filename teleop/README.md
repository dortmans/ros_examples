# teleop

Teleop using a gamepad.
Works for Microsoft Xbox 360 (wired) gamepad or compatible, like Logitech F310 (used in XInput Mode).

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

Launch teleop example as follows:
```
roslaunch teleop teleop.launch joy_dev:=1
```

Use the correct value for joy_dev (0 or 1).

## References

- http://wiki.ros.org/joy
- http://wiki.ros.org/joy/Tutorials/ConfiguringALinuxJoystick
- http://wiki.ros.org/joy_teleop
