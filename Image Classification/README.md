# Deep-Learning in Practice with Python and LUA (BMEVITMAV45)
## Fourth assignment

The goal is to further teach a pre-trained CNN network:
* Select three categories from the Google Open Image Dataset (GOID: https://storage.googleapis.com/openimages/web/index.html) and download 600-600 images per category.
* Load a pre-trained network (eg Inception v3, VGG, ResNet) and train it (transfer learning) with the three selected categories:
   * Only the final fully-connected layers should learn first.
   * Then train the network further with the upper layers of the convolutional layers included (the lower ones do not).
* Evaluate the effectiveness of the solution on a separate test database with the three selected categories.
* Pay attention to that
   * attach the method and script of the image download (if you have your own code),
   * 400-400 images in the teaching database, 100-100 in the validation, 100-100 in the test,
   * use the same pre-processing procedure as used for the pre-trained network.

You can use any deep learning framework. Comment your solution in detail and include the output (log file).
The description and comments should be in English!

For help, we recommend using the following resource: https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html


### Deadline: 10 November 2020

### Result: 19/20 + 1 extra point

