# Covid-19_Detection-using-X-ray_images

Detection of covid-19 using x-ray_images of Chest using Deep Learning.

It consist of samples an open source dataset of X-ray images for patients who have tested positive for COVID-19 and 
normal (i.e., not infected) X-ray images from healthy patient.
Training a CNN to automatically detect COVID-19 in X-ray images on these datasets by comapring the both Normal and Covid-19 X-ray images. 

Dependencies:-
1.Tensorflow
2.Opencv(cv2)
3.Matplotlib
4.sklearn
5.Numpy
6.Pandas
Links to installation guide of Dependencies:-
1. https://docs.anaconda.com/anaconda/user-guide/tasks/tensorflow/
2. http://web.cecs.pdx.edu/~fliu/courses/cs410/python-opencv.html
3. https://anaconda.org/conda-forge/matplotlib
4. https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html
5. https://scikit-learn.org/stable/install.html

1. First Method :-
link to download dataset:- https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge11
download the dataset from above link
use dataset_extract jupyter notebook script to extract images form dataset and then use build_dataset jupyter notebook to create the dataset with labelling for taining CNN.
use CNN_model jupyter notebook to train the model.
2. Second :
You can directly use my dataset to train the model
