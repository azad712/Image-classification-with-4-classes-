# Image-classification-with-4-classes-
This is an Image classification project, with images of people in 4 classes, a person without any sunglasses and not wearing a mask, a person with sunglasses but not wearing a mask, a person without sunglasses but wearing a mask,  a person wearing both, the sunglasses and mask. 
Project incorporates Transfer Learning Technique using pre-trained Resnet50 model. Implementation is in Pytorch and Jupyter notebook. Dataset is manually created by me, by going through google images and other publicly available datasets. 
The unique part about this project is that training is done on only 500 diverse images, including all the 4 classes, which is considered as a very small dataset for deep learning task.
Despite very small dataset for training, the overall accuracy achieved is 88 % on Training dataset comprising of 200 images.
Regularization techniques of L1, L2 and Dropout has been incorporated.
