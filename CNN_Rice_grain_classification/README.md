# Classification of rice varieties with deep learning methods
## Observations:
- Total of 75000 images, 15000 from each variety, total 5 categories of Rice
- {'Arborio': 0, 'Basmati': 1, 'Ipsala': 2, 'Jasmine': 3, 'Karacadag': 4}
- Train & Test breakup is 12000 and 3000 (80-20)
- Firstly created the TRAIN & TEST folders and sub-folders based on classes.
- Using the shutil library copied images from source to respective directories maintaining a 80-20 split.
- Loaded the image data using ImageDataGenrator class object and methods.
- CNN model was created and Results after 5 epochs with 1 Conv layers, 1 max pooling and 3 Dense layers is as follows:
    - Train accuracy: 0.9546 - loss: 0.1304
    - Test accuracy: 0.8989 - loss: 0.2438
