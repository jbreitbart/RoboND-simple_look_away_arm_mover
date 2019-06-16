# Udacity RoboND simple arm mover

## Simple mover

Do not forget to install alle dependencies: `rosdep install -i simple_arm`

Test movement: `rosservice call /arm_mover/safe_move "joint_2: 2.0"`

## Arm mover

Correct parameter: `rosparam set /arm_mover/max_joint_2_angle 1.57`

Show the Camera: `rqt_image_view /rgb_camera/image_raw`

Move the arm:
```
rosservice call /arm_mover/safe_move "joint_1: 1.57
joint_2: 1.57"
```

## Look away
