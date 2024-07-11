# Fruit Classification using CNN
## About Dataset
### Objective 
- To classify images of different fruits using a CNN model.
### Dataset
- Total number of images: 22495.
- Training set size: 16854 images (one fruit or vegetable per image).
- Test set size: 5641 images (one fruit or vegetable per image).
- Number of classes: 33 (fruits and vegetables).
- Image size: 100x100 pixels.
- Training data filename format: Many images are also rotated, to help training.
### Content
- train - the training folder that contains 33 subfolders in which training images for each fruit/vegetable are located. There is a total of 16854 images.
- test - the testing folder that contains 5641 testing images
### Results:
- CNN model was created and Results after 10 epochs with 3 Conv layers, 3 max pooling and 3 Dense layers is as follows:
    - Train accuracy: 0.9927- loss: 0.0253
    - Test accuracy: 0.9905- loss: 0.0287
