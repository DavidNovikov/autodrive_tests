Visualize a point cloud and display the respective 3D bounding boxes of various objects
- Visualize the point cloud (.bin files)
- Plot the various objects given their 3D bounding box information
- (Optional) The visualization should allow the user to view the entire point cloud from different angles and perspectives
- Visualize pc1.bin with bb1.txt and pc2.bin with bb2.txt and submit a screenshot of the working visualization (example shown in the top part of sample_results.png)

Note: 
- Point cloud files (.bin) are given in the form of N x 4 with numbers in np.float32 format
- The images corresponding to each point cloud is provided as a reference
- Bounding box files have table headings. X is forward, Y is left, Z is upwards. You can assume there is only 1 rotation for the bounding box which is around the Z axis.

Important Updates: 
- We highly recommend completing the challenge using the plotly library
- Consider using Scatter3D and adjusting the aspect ratio when plotting
- For a better visualization, change the color of the points based on the distance
- Plotting bounding boxes are now optional but if you can figure it out on plotly, that'll be great