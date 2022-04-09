Our preprocessing was done exclusively in MATLAB.

Our dataset was sourced from Kaggle: https://www.kaggle.com/c/dogs-vs-cats/data however we only used the labeled train data (12,500 cats and 12,500 dogs). 

Initially, we loaded our Kaggle data into Matlab with the load_data_200_by_200.m file which saved our data into DATA.mat which includes two matrices: one with all cat images and one with all dog images. 

We found it easier to load into Python if we had four matrices: cat train images, cat test images, dog train images and dog test images. We used split_80_20.m on our DATA.mat file to create our 80_20_DATA.mat file which we used in Python for our models.

For our CNN models, we required our scaled 200 x 200 x 3 images to be in folders so we loaded 80_20_DATA.mat into Matlab and ran GET_TO_FOLDERS.m in order to create the folders seen here: https://drive.google.com/drive/folders/1CyKaRINviJZZMCzP2rhxHOAZBRELGAnD?usp=sharing
