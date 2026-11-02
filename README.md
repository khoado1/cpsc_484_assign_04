# cpsc_484_assign_04

• Name of student: Khoa Do
• Operating system/CPU architecture/development environment used. Include version of OS and architecture type, as this helps me with compilation issues.:
MacOS, Apple M4 Pro, Macbook Pro

• Special instructions on how to compile and run your code if different from the instructions provided.: N/A

• Did you collaborate with anyone in the class? If so, describe who you worked with and what assistance was given or received.: N/A

• Were there any references, books, websites, or other resources that you found particularly useful?: Coding video session

• An explanation of why moveKey() returns a new index and what can happen if it returns the original index.: moveKey has to return a new index so that the render can re-evaluate it and if it returns with the original index, nothing happens.

• An explanation of gimbal lock in your own words and how the camera’s pole safeguard relates to orientation singularities.: gimbal lock allows for the camera to stay stable and fixed even if the platform that it is on is moving.

• Are there any known problems with your implementation? If so, describe them.: I am not sure but there might be an issue with moving the keyframe


• A short guide identifying which shapes demonstrate translation, rotation, scale, easing, and looping. Identify the track with at least four keys and the intervals where the easing differences are clearest.: cube has all the behavior.  There's a second video where the cube is using ease in-out.

• Any known problems, how to reproduce them, and what you think is causing them.: possible issue with moveKey

• Any additional functionality or comments about the assignment.: n/a