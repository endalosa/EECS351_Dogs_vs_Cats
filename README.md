## EECS 351 Dogs vs Cats Classification Demo

### Description

This demo will create an untrained VGG-16 Convolution Neural Network (CNN) model and train it on 100 images of cats and 100 images of dogs. Then we will test the model on 20 cats and 20 dogs and examine the accuracy, loss and where and how the model fails.

### Dependencies

You will need Python 3.8 installed via Anaconda Navigator. In addition, you need these libraries downloaded: torch 1.11.0 and tensorflow 2.8.0.

### Requirements

Make sure both the "cats_and_dogs_filtered" folder and the Jupyter notebook file are in the same directory. Update the path to the directory where it says <YOUR_PATH_HERE>: 

```
##prepare iterators
train_it = datagen.flow_from_directory(./<YOUR_PATH_HERE>/cats_and_dogs_filtered/train' ...)
test_it = datagen.flow_from_directory(./<YOUR_PATH_HERE>/cats_and_dogs_filtered/validation' ...)
```
```
pathCat = "./<YOUR_PATH_HERE>/cats_and_dogs_filtered/validation/cats/"
loadImages(pathCat, 0, 1)
pathDog = "./YOUR_PATH_HERE>/cats_and_dogs_filtered/validation/dogs/"
loadImages(pathDog, 20, 21)
```

### Expected Output

Watch this YouTube video for a walkthrough of running this demo and what takeaways we came to: [link](https://www.tbd.com)
