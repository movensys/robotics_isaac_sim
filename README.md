# 3D Files for Movensys Manipulator

This repository provides USD files for running `movensys_isaac_manipulator` in NVIDIA Isaac Sim.

## 1. Quick Start Guide

### 1-1. Environment Setup
```
export ROS_DOMAIN_ID=70
export ROS_DISTRO=humble
export RMW_IMPLEMENTATION=rmw_cyclonedds_cpp
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/humble/lib

source /opt/ros/humble/setup.bash
```

### 1-2. Running Isaac Sim

1. Run Isaac Sim.
```
~/isaacsim/isaac-sim.selector.sh
```
2. Activate `isaacsim.ros2.bridge`
3. Click `Start`
4. Open USD file: `~/robotics_isaac_sim/<usd_name>.usd` as your test scenario.
5. Click `Play` on the left side.


## 2. Related Repositories

- [movensys_isaac_manipulator](https://bitbucket.org/movensys/movensys_isaac_manipulator) - Isaac Manipulator ROS2 package
