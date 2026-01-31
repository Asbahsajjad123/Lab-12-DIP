# Lab-12-DIP
1.	Apply global, local, adaptive thresholding.
2.	Perform K-means segmentation (k=2,3,4).
3.	Perform Mean Shift segmentation.
4.	Compare results visually.
5.	Discuss method strengths.
# Code Explanation
This code demonstrates image thresholding and segmentation techniques using OpenCV in Google Colab. First, an image is uploaded, read in color, and converted to grayscale for thresholding operations. Three thresholding methods are applied: global thresholding with a fixed threshold value, Otsu’s thresholding which automatically selects an optimal threshold based on image histogram, and adaptive thresholding which computes local thresholds for different image regions. After that, image segmentation is performed using K-means clustering, where the image pixels are grouped into 2, 3, and 4 clusters based on color similarity, producing different levels of segmentation detail. Mean shift segmentation is also applied, which segments the image by smoothing and clustering pixels in both spatial and color domains. Finally, all results—including the original image, thresholded outputs, and segmented images—are displayed together for visual comparison to show how different segmentation methods affect the image.
