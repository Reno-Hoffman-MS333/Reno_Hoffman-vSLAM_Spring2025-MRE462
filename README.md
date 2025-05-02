# Reno_Hoffman-vSLAM_Spring2025-MRE462


Looking to this vSLAM project is broken into 2 parts Code 1 is a examination and implementation of MatLab Monocular VSLAM and Code2 is my attempt at said implementation.


1. VSLam example

  I.Generalized setup
  Example code gives imageDatastore creation with downloaded images that exist in vSlam1.m code

  II. Results
 Results are in screenshots of Mapping initialization, Construction then with computed trajectories both estimated optimized and compared to ground truth provided. Additonal initilization function with feature extration function called in terminal before program run


2. My SLAM Implementation

   I. Data set
   Data set was taken from a video file of my desktop in my dorm then converted to individual jpg files placed into an image folder for the program to then work through currently residing in FunctionsandImageData/VSLAMIMAGES/. All extra functions needed for the program also Reside in Functions folder. Video length was only about 30 seconds with a total of 110 Frames used for local mapping.
   
   II. Results
Results folder in Code2 contains information from sections that I was able to aquire in my testing such as map initilization, refined inital reconstruction, then the current local mapping process that seems to be incomplete due to issues with some functions not pathing properly causing the mapping to end once on frame 25.
   
   III. Errors
   In the results folder of Code2 shows image file with specific error in function pathing that I was not able to resolve. 
   
