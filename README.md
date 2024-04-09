<h1>Brain Tumor Detection with CNN</h1>

<h2> 🔧 Technologies & Tools </h2>
 <div>
 <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/>
  <img src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252"/>
  </div>
 
 ---
 
 <h2 ><img src="https://img.icons8.com/office/30/000000/training.png"/> &nbspProject Introduction and Objectives: </h2>
 
#### The goal of this project is to develop a Convolutional Neural Network (CNN) model to classify MRI scans as either containing a tumor or not. The model utilizes both CNN and Deep Neural Network (DNN) for binary classification, with accuracy serving as the primary metric to assess its performance.

Data set Description:

The images in this project use the Kaggle data set:[Brain MRI Images for Brain Tumor Detection](https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fnavoneel%2Fbrain-mri-images-for-brain-tumor-detection%3Fselect%3Dyes)。

Two categories in total::

- NO - no brain tumor
- Yes - has brain tumor

Note: The author of this data set did not indicate the source of the brain tumor images.

### View the project code : [BrainMRI](https://github.com/chrisluo5311/Team_Image_Recognition/blob/master/BrainMRI.ipynb)
 
 ---

### Software version:
|  software  |  version  |  
|:------:|:--------:|
|  Python  | `3.11.5`   | 
|  Matplotlib  | `3.7.2`   | 
|  Numpy  | `1.25.2`   | 
|  Pandas  | `2.0.3`   | 
|  Tensorflow  | `2.12.1`   | 
|  keras  | `2.12.0`   | 

 ---

 <h2 ><img src="https://img.icons8.com/office/30/000000/training.png"/> &nbspReference: </h2>

|  Topic  |  Explanation  |  
|:------:|:--------:|
|  kaggle data set  | Brain MRI Images for Brain Tumor Detection  | 
|  Data set explanation  | 253 files in total, including 98 files for no and 155 files for Yes.    | 
|  Reference  | [Brain MRI](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection?select=yes)   | 


---

<h2><img width="32" height="32" src="https://img.icons8.com/nolan/64/summary-list.png" alt="summary-list"/> &nbspSummary: </h2>

This project combines a CNN model classification problem (used to predict whether a subject has a brain tumor) and a computer vision problem (used to automate the process of cropping brains from MRI scans). The final accuracy is much higher than the baseline of 50% (random guessing). However, this accuracy can be further improved by increasing the number of training images or by adjusting model hyperparameters.

