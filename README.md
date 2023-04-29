# Exposure_Detection
Here we are going to detect the exposures of images using machine learning models
#
You can find the training dataset used containing two folder "INPUT_IMAGES" which has the input images and "GT_IMAGES" which has the target (or correct exposure )images.
Using this we create a csv file containing mean , variance and label of each of the images (More details in .pdf given below and code is given as Dataset_create.py)
Using the csv file we are training an ML model from scractch (without using scikit for any purposes) to find whether an image is Over Exposed or not.
Code is given in Exposure_Detection.ipynb
