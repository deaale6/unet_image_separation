# unet_image_separation

## Task
The project aims to separate an image obtained as a sum of two images into its original components. 
The two images, img1 and img2, come from different datasets: mnist and fashion_mnist, respectively.
The network takes the sum img1+img2 as input and returns the predicted components hat_img1 and hat_img2. 
The chosen architecture is U-NET.

## Results
The metric used to evaluate the project is the mean squared error between the predicted and ground truth images. 
