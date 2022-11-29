# Image-denoising-and-classification

######################################################################################################################
Part A - Image Denoising
Filename: Assignment Part A.ipynb
This notebook was created in Jupyter in an Anaconda3 environment with Python version 3.7.

# Dependencies
	* os
	* opencv
	* scikit image
	* matplotlib

# Dataset
* The dataset used for Part is provided and is called Part-I-Dataset-denoising.zip
* Dataset contains 3 levels of noisy  images that cneeds to be denoised and original images.

# GENERAL NOTES
IMPORTANT: The code contains references to file paths which should be edited in the notebook before it is executed.
These are:
* The root directory where the notebook will be executed from.
* The following folders should be expressed relative to the root folder:
	* A folder containing all the original images
	* Folders containing images for each of the noisy levels
	* Output folders for denoised images for each of the noisy levels per denoising method
	* A Results folder which will contain a CSV file with the results

#1. Write codes with the following denoising methods 
     a. Mean filter 
     b. Median filter 
     c. Wavelet 
     d. Deep learning (you are free to choose any pre-trained model you want – but you need to justify why did you select           this model). You are not expected to train a new model for this part.
     
# 2. Compare the original and denoised images using the following metrics (you are free to use any library):
     a. Mean Squared Error (MSE) and 
     b. Structural SIMilarity (SSIM) index     
     
# 3. Generate and report results (some sample images and graphs/tables)  

########################################################################################################################

Part B - Image Classification
Filename: Assignment Part B.ipynb

# Dependencies
	* numpy
	* keras
	* matplotlib
	* tensorflow

# Dataset
CIFAR-10 available here: https://keras.io/api/datasets/cifar10/

# GENERAL NOTES
* The code is contained in a notebook created in Google Colab.
* The notebook settings were adjusted to enable the use of a GPU.
* The code contains one path to the image on which the classification is applied.
* This path should be adjusted and point to the image of choice.

1. Load the CIFAR10 small images classification dataset from Keras inbuilt datasets (https://keras.io/api/datasets/cifar10/). 
   Display 10 random images from each of the 10 classes (the images should change in every run).
2. For the classification (10 image classes), write Python code to create a basic CNN network of your choice (can be anything from practical 7, LeNet, AlexNet etc.) 
3. Train and test the network and report the training loss, training accuracy and test accuracy for various epochs. 
4. Improve the architecture by changing the parameters, including but not limited to, learning rate, epochs, size of the convolution filters, use of average pooling or max-pooling etc.
5. Improve the architecture by introducing more convolutional and corresponding subsampling layers. 
6. Your final code should accept single image on the trained network and produce the output class.

######################################################################################################################
