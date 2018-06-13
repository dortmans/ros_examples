# Joy

The [joy package](http://wiki.ros.org/joy) contains joy_node, a node that interfaces a generic Linux joystick to ROS. This node publishes a "Joy" message, which contains the current state of each one of the joystick's buttons and axes.

## Gamepads

Applicable Gamepads:
- [Microsoft Xbox360](https://en.wikipedia.org/wiki/Xbox_360_controller)
- [Logitech F310](https://www.logitechg.com/en-us/product/f310-gamepad) (in XInput mode)

![Xbox360 controller[(Xbox360controller.png)

## Buttons

| Button |     Name      | Value | Remark |
| ------ | ------------- | ----- | ------
|   0    |       A       |  0/1  |        |
|   1    |       B       |  0/1  |        |
|   2    |       X       |  0/1  |        |
|   3    |       Y       |  0/1  |        |
|   4    |       LB      |  0/1  |        |
|   5    |       RB      |  0/1  |        |
|   6    |      BACK     |  0/1  |        |
|   7    |      START    |  0/1  |        |
|   8    |      GUIDE    |  0/1  | Xbox / Logitech |
|   9    |   LeftStick   |  0/1  |        |
|   10   |   RightStick  |  0/1  |        |

## Axis

|  Axis  |     Name      | Value       | Remark |
| ------ | ------------- | ----------- | ------ |
|   0    |  LeftStick X  |  1.0 <=> -1.0 | left <=> right |
|   1    |  LeftStick Y  | -1.0 <=>  1.0 | down <=> up |
|   2    |  LeftTrigger  |  0.0 / 1.0 <=> -1.0 | unused / no-press <=> max-press |
|   3    |  RightStick X |  1.0 <=> -1.0 | left <=> right |
|   4    |  RightStick Y | -1.0 <=>  1.0 | down <=> up |
|   5    |  RightTrigger |  0.0 / 1.0 <=> -1.0 | unused / no-press <=> max-press |
|   6    |   D-Pad X     |  1.0 / -1.0  | left / right |
|   7    |   D-Pad Y     | -1.0 / 1.0 | down <=> up |


