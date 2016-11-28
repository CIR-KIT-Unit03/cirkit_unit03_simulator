# cirkit_unit03_simulator [![Build Status](https://travis-ci.org/CIR-KIT-Unit03/cirkit_unit03_simulator.svg?branch)](https://travis-ci.org/CIR-KIT-Unit03/cirkit_unit03_simulator) [![Slack](https://img.shields.io/badge/Slack-CIR--KIT-blue.svg)](http://cir-kit.slack.com/messages/unit03_simulator)
Gazebo simulation for CIR-KIT-Unit03

## Installation
#### **!! CAUTION !! : **DO NOT INSTALL** this repository **ALONE**.  
We highly recommend install this repository with `[cirkit_unit03_pkg](https://github.com/CIR-KIT-Unit03/cirkit_unit03_pkg)`.

#### For the developers only
##### 1. Create **catkinized**  workspace.
##### 2. Clone this repository.
```bash
$ cd <catkin_ws>/src
$ git clone https://github.com/CIR-KIT-Unit03/cirkit_unit03_simulator.git
```
##### 3. Download required packages by wstool.
```bash
$ cd <catkin_ws>
$ wstool init src
$ wstool merge -t src src/cirkit_unit03_pkg/cirkit_unit03_simulator.rosinstall
$ wstool update -t src
```
##### 4. Download depended packages by rosdep.
```bash
$ cd <catkin_ws>
$ rosdep install -i -r -y --from-paths src --ignore-src
```
##### 5. Build packages, and set the path for the packages.
```bash
$ cd <catkin_ws>
$ catkin_make
$ source devel/setup.bash
```
