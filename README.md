This project is done as part of Advanced Computer Vision - MCEN 5228.

# Abstract
 In this project we are
 stitching together images to form a panorama. This process is
 done by first extracting corners of images, then we select a subset
 of corners that are evenly spread through the image via the
 ANMS algorithm, subsequently we create feature vectors from
 images patches around corners. We then match corners between
 images by a similarity metric (Sum squared differences) to find
 points that correspond between images. Finally we estimate a
 homography matrix using RANSAC to handle outliers before
 stitching the images together with the homography matrix

 # Output
 1. Detecting Corners
 - ![image](https://github.com/user-attachments/assets/32d14e19-a2c9-46c0-bae4-cee5b9ab760a)

 2. Feature Matching
  - ![image](https://github.com/user-attachments/assets/62caea46-7d45-441f-9b1a-ef51df2b59c8)

3. Refined Feature Matching
- ![image](https://github.com/user-attachments/assets/032eef88-b700-4ca9-a0e9-858300d29a91)

4. Panorama Stitching from our Feature Matching Algorithm
- ![image](https://github.com/user-attachments/assets/0cb50490-eec2-461d-a63e-953c327eaa15)

5. Panorama Stitching using SIFT
- ![image](https://github.com/user-attachments/assets/c11e2591-2c56-412d-b6bb-d5bbd2a17d16)
- ![image](https://github.com/user-attachments/assets/28028465-b88e-4888-8f28-f96fdda4b374)



 

