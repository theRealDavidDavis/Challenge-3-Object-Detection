# Challenge-3-Object-Detection
The challenge consisted of training a convolutional neural network to detect the presence of orange traffic cones in an image using a base data set of 383 JPEG images. 

Using ImageDataGenerator with a rotation of up to 15 degrees and horizontal mirroring on, I generated more data so that we could train on a data set of 2,000 JPEG images which was validated with 800 images. 

These images were fed into a Keras sequential model consisting of 3 convolutional neural networks with a regular neural network at the end. 

The results CSV files was uploaded to the Kaggle classroom submission for this challenge where the accuracy of this model was 93.1%. Upon analyzing my model with the validation set, I found that the model was incorrectly classifying car rear lights as cones. 
