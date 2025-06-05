# SummerResearch2025

## Project Overview
Last summer I setup a connection between a VR headset and a physical robot. When this got implemented with the delay compensation algorithm we found that the robot needed to be more precise closer to target and faster the further away from the target the robot is. Since the user is naturally going to be looking towards the destination of the robotic hand, this project will use the distance between the position of the robotic gripper and the point at which the user is looking at to determine how fast the robot should move.

## Task Lists
### Completed
- Integrate the Meta quest 3 VR headset with Unity

### In Progress
- Generate a Heapmap based upon the depth at which objects are from the camera (in Unity) --> Active task
- Learn the Unity Robotics setup and create an active scene for the user (6-7 DoF robot, preferably 7 DoF) --> Don't really need this. Just really an end effector

### Next Steps
- Configure the gaze interaction with the neon eye tracker to map out where the user is looking at
- Utilize the depth Heapmap with the Gaze point to create an object point cloud to determine where (what object) the user is looking at
- Calculate the distance between where the user is looking at and the position of the robotic gripper
- Utilize the distance between the user's eye point --> TODO: Will figure out next steps when we get to this phase
