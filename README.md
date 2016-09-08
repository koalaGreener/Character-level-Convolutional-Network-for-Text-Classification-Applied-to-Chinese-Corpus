#Requirements

Python2 / Python3

Keras

Tensorflow

(Run this model under CUDA will significantly increase the training speed, Nvidia graphic card required.)

#Components

This repository contains the following components:

Models: Different model settings for the various dataset. There are four different folders, which are 2008_models, Chinese_character, pinyin_formatA, pinyin_formatB. 2008_models represents the task 1 's model which is applied to Zhang's dataset. The other models are all for task 2, and the datasets are constructed for this paper. 

Dataset: The dataset for proposed model. The 2008_dataset is constructed by Zhang in his paper, while the 2012_dataset is constructed for this paper, including pinyin format and Chinese character dataset.

Data Preprocessing: Some source code for data preprocessing, and it can be used to reproduce the dataset using Sogou news articles. 


#Example Usage

1.Install the Keras and switched the backend to Tensorflow.

2.Download the dataset from google drive and put both the training set and test set into the data folder.

3.Import the ipynb files into the IPython Notebook, and start to train the models.


#Licence

MIT
