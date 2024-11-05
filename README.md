This project is done as part of Advanced Computer Vision - MCEN 5228.

#Abstract
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
