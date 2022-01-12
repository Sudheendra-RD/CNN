# Data Augmentation using Keras

Data Augmentation is a process of generating random images from a given image.
This is done when the images are very less and the CNN cannot differentiate those images.

In data augmentation, we use a particular image and using Keras ImageDataGenerator library, create random images which might be:
1. rotates
2. shrinked
3. zoomed in/out
4. flipped (i.e. mirror image)
5. shifted slightly from its original position
