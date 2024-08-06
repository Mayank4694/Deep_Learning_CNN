# Classification of rice varieties with deep learning methods
## Observations:
- Total of 75000 images, 15000 from each variety, total 5 categories of Rice
- {'Arborio': 0, 'Basmati': 1, 'Ipsala': 2, 'Jasmine': 3, 'Karacadag': 4}
- Train & Test breakup is 12000 and 3000 (80-20) for each class
- Firstly created the TRAIN & TEST folders and sub-folders based on classes.
- Using the shutil library copied images from source to respective directories maintaining a 80-20 split.
- Loaded the image data using ImageDataGenrator class object and methods.
- The Model with 5 nos. of conv2D and 4 nos. of MaxPooling2D layers followed by a Flatten and a FC layer of 128 neurons and then output layer.
- Test loss and accuracy are: 0.0854, and 97.27% respectively
- Train loss and accuracy are: 0.0755 and 97.41% respectively
- The above results were obtained after training on 60,000 images for 3 epochs and testing on 15,000 images
- The classification report on test data shows f1 score >0.99 for all classes.
- Accuracy can be further improved state of art models and further fine tuning the params or increasing the epochs.
