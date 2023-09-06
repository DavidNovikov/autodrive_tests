Create an oriented bounding box that is level with the ground
-this task is meant to capture a bounding box that is rotated, but is level with the ground. The test files are pcd1.pcd, pcd2.pcd, and pcd3.pcd
-if we take a pcd (shown in original_pcd.png) and give it an axis aligned bounding box (axis_aligned.png), it fails to capture the rotated nature of the turned object. Conversely if we get a oriented bounding box (oriented.png), it seems like the object is partially flipped as it moves.
-your task is to get a bounding box which is rotated with the object, but is level with the ground (as shown in rotated_but_level_with_ground.png)
-essentially your bounding box should look like a box thats been rotated on the ground.
-for this task it is sufficient to visualize the bounding boxes in your code and we can manually inspect them in the open3d visualizer