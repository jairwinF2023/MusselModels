Howdy,

Welcome to the Mussel Image Classifier code set. Below is a run-down of each:

1. MusselClassifier
   
   MusselClassifier is the Classification model of the bunch. From a given set of images, particularly those of single extracted mussels, it can create a binary class of 0 or 1. In this case, alive or questionable (manual review recommended)
   
2. MusselModel256
   
   MusselModel256 contains a failed extraction model that tries to extract images by creating a grayscale mask then using the mask to determine entities to be extracted for classification.
   
3. QuickCropper
   
   QuickCropper provides a pretrained model that is able to extract images from a larger image if it is above a given threshold of certainty. This model does not 

A recommendation prior to continuing this problem would be to look into MNIST classification for an introductory base for those unfamiliar with Pytorch. A modified version that addresses rotation and skewness of items can be found here: https://github.com/jairwinF2023/STAT4744Final
