There are many signers all around the world who use technology and social media that can’t recognize their native language.
The aim of this project is to help bridge the gap between the Deaf community and technology.
We used a Convolutional Neural Network (CNN) and tried to classify 6 different handshapes acquired from videos of native signers. 
After running the baseline model, we ran the model seven more times by changing the filter sizes and the number of fully-connected layers and the size of the data used to train the model. 
The highest accuracy we achieved is 99.43%. 


The files in this repo include jupyter notebooks. One of the notebooks is the baseline model with one neural network layer.
Other notebook is our experiment notebook. We changed the datasize and the number of filters in the first convolution layer.
The notebook "crop_filmstrips" includes a code we used during preprocessing to crop the filmstrip images we extracted from ELAN to
seperate images. The last notebook contains a code to write a folder of images into a csv file in the form of arrays.

We suggest creating a tensorflow environment to run this model. 
