# Smiling-Face
A deep learning model that classifies frontal face images into whether they are smiling or not

#DATASET

The dataset for the project was collected from Kaggle.
The dataset contains two directories images. One contains images of smiling faces and other of straight faces. 

#METHOD

After loading the data using ImageDataGenerator from tensorflow, and preprocessing it we pass it to the model.
The preprocessing steps include:
1. Image resizing
2. Selecting an appropriate batch size
3. Splitting the dataset into train and test directories

Then, the CNN model, known for its robust feature extraction capabilties is used to fit the dataset.
An accuracy of 90% was achieved for validation data.
