# automatedGlueUp

This repository contains the code needed to automate the placement of a silicon wafer onto a moveable stage for glueing. The robot used is a MECADEMIC 6-Axis Robot Arm model MECA500-R4.

The steps:
1) Locate the unglue-d wafer and identify the features used for alignment.
2) Pick up the wafer using the air-conttrolled gripper.
3) Carry the wafer to the stage, using the openCV to identify the landing zone.
4) Return robot to resting state.

