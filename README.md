# `teleop_tools`

A set of generic teleoperation tools for any robot.

This contains the following teleoperation tools:

* `joy_teleop`, a generic joystick interface for topics and actions
* `key_teleop`, a lightweight console keyboard teleoperation utility
* `mouse_teleop`, a pointing device (e.g. mouse, touchpad) teleoperation utility

## Changes

I hacked up the axis mapping portion of `joy_teleop`'s topic command portion so I can use typical racing game controls on my robot.
This is coupled with the parameters in [this configuration file.](https://github.com/ray-quasar/f1tenth-humble/blob/main/f1tenth_stack/config/joy_teleop.yaml)

For an Xbox controller, this means that the right trigger is throttle position and the left joystick is steering and throttle direction.
