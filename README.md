# Urban Sounds Classification 
Koç Holding Deep Learning Bootcamp

In this project, we use “UrbanSounds8K” dataset, the sounds heard in the cities.

For access the all data, you can click this [link](https://urbansounddataset.weebly.com/urbansound8k.html). It downloads a compressed tar file of size around 6GB.

You can access the spectrograms of the data set we used by clicking the [link](https://drive.google.com/drive/folders/1xey3vAVNDjWxnSfhuUsf_5dGANZWmCog).

We will prepare and train a **CNN (Convolutional Neural Network) model** by using these spectrograms.

## Steps of our project

### -->Importing the Required Libraries
Numpy, Pandas, Matplotlib, Os, Google.colab, Opencv and Tensorflow

### -->Loading of Dataset
#### Reading csv file from my Drive
#### Access to spectrogram files from my Drive

### -->Preprocessing - Notebook
a. By reading the images (spectrograms) in order, grayscale transformation, resizing and normalize.

b. Save images with their tags in [image, tag] format.Add to the list and shuffle the data

c. Create the X_train, y_train, X_val, y_val, X_test and y_test datasets.

d. Save these datasets to your computer.

### -->Preparing and Training of Model by using CNN  - Notebook
a. Prepare a CNN model.

b. Train the model using the data you have prepared.

c. Print the model's performance metrics, loss and accuracy graphs on the screen.
