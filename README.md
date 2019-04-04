# 3D-Object-Segmentation-and-Extraction-with-point-clouds

The video shows our current progress for the subsystem. As you can see we first define a Region on interest in first video for the raw point cloud. After preprocessing and removing noisy data, we use techniques such as RANSAC to segment out the ground planar surface and then cluster the different segmented objects as seen in the 3rd video. Major work was done to make this whole pipeline real- time and integrate it with ROS. 

![1](/results/1.png)


![2](/results/2.png)


![3](/results/3.png)
