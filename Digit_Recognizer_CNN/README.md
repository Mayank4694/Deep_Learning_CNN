# MNIST digits classification using CNN
## About Dataset
### Source
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.

Dataset link: https://www.kaggle.com/datasets/scolianni/mnistasjpg
### Objective: 
To classify images of handwritten digits (0-9) using a CNN model.
### Summary

- Data Preparation: Created TRAIN and TEST directories and its sub-folders (classes). Using shutil, moved files in the ratio 80-20 respectively for each class.
- Model Building: Defined a CNN architecture suitable for digit recognition.
- Model Training: Trained the model using the training data.
- Evaluation: Evaluated the model on the test data and plotted the training history.
- Prediction: Made predictions on new images using the trained model.
### Observations
- The Digit Dataset has 10 classes from 0,1,2...9.
- Firstly created the TRAIN & TEST folders and sub-folders based on classes.
- Using the shutil library copied images from source to respective directories maintaining a 80-20 split.
- Loaded the image data using ImageDataGenrator class object and methods.
- CNN model was created and Results after 10 epochs with 3 Conv layers, 3 max pooling and 3 Dense layers is as follows:
    - Train accuracy: 0.9058- loss: 0.2925
    - Test accuracy: 0.9524- loss: 0.1627
