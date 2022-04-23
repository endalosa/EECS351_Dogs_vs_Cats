## EECS 351 Dogs vs Cats Project

### Description

Create a highly accurate model that can predict whether an image is a cat or a dog using Digital Signal Processing (DSP) techniques, image processing, and deep learning. We first preprocess the dataset sourced from Kaggle: https://www.kaggle.com/c/dogs-vs-cats/data (see Preprocessing folder) and then attempt Decision Tree and KNN in both MATLAB and Python (see KNN_DecisionTrees folder). We then run a 1 layer CNN and a VGG-16 model and compare and contrast models (see CNN folder).

### Dependencies

You will need MATLAB 5.3.1 with the Statistics toolbox. You will need Python 3.8 installed via Anaconda Navigator. In addition, you need these libraries downloaded: torch 1.11.0 and tensorflow 2.8.0.

### Requirements

For MATLAB, make sure the .m file and the DATA.mat file used are in the same directory. For Python files, make sure both the "cats_and_dogs_filtered" folder and the Jupyter notebook file are in the same directory. Update the path to the directory where relevant in files, especially during sections like this:

```
##prepare iterators
train_it = datagen.flow_from_directory(./<YOUR_PATH_HERE>/cats_and_dogs_filtered/train' ...)
test_it = datagen.flow_from_directory(./<YOUR_PATH_HERE>/cats_and_dogs_filtered/validation' ...)
```

Additionally, remove this section if you are not running on Google Colab but instead on your local Jupyter Lab:

```
from google.colab import drive
drive.mount('/content/drive')
```

### Expected Output

All expected output is published on our website: https://sites.google.com/umich.edu/classifying-cats-vs-dogs/home?authuser=1
