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
 
 <h2 ><img src="https://img.icons8.com/office/30/000000/training.png"/> &nbsp專案簡介及目標: </h2>
 
#### 這個專案的主要目的是建立一個卷積神經網絡(CNN)模型,根據MRI掃描判斷受測者是否患有腫瘤。本專案使用了CNN和DNN對這個二元問題進行建模與訓練。最後將以準確度作為評估模型效能的指標

資料集說明:

本專案的影像使用的是Kaggle資料集[Brain MRI Images for Brain Tumor Detection](https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fnavoneel%2Fbrain-mri-images-for-brain-tumor-detection%3Fselect%3Dyes)。

總共分兩類:

- NO - 沒有腦腫瘤
- Yes - 有腦腫瘤

註: 該資料集作者並未說明腦腫瘤影像的出處

### View the project code : [BrainMRI](https://github.com/chrisluo5311/Team_Image_Recognition/blob/master/BrainMRI.ipynb)
 
 ---

### 安裝軟體對應版本:
|  軟體  |  版本  |  
|:------:|:--------:|
|  Python  | `3.11.5`   | 
|  Matplotlib  | `3.7.2`   | 
|  Numpy  | `1.25.2`   | 
|  Pandas  | `2.0.3`   | 
|  Tensorflow  | `2.12.1`   | 
|  keras  | `2.12.0`   | 

 ---

 <h2 ><img src="https://img.icons8.com/office/30/000000/training.png"/> &nbsp參考鏈接: </h2>

|  標題  |  說明  |  
|:------:|:--------:|
|  kaggle資料集  | Brain MRI Images for Brain Tumor Detection  | 
|  資料集解釋  | 總共253個檔案，其中no有98個檔案，Yes有155個檔案    | 
|  資料鏈接  | [Brain MRI](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection?select=yes)   | 


---

<h2><img width="32" height="32" src="https://img.icons8.com/nolan/64/summary-list.png" alt="summary-list"/> &nbsp總結: </h2>

這個專案結合了CNN模型分類問題（用於預測被測主體是否患有腦腫瘤）和計算機視覺問題（用於自動化從MRI掃描中裁剪腦部的過程）。最終的準確度遠高於50%的基準線（隨機猜測）。然而，這個準確度可以透過增加訓練圖片的數量或通過調整模型超參數來進一步提高。

