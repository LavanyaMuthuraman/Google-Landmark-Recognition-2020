---
# Google Landmark Recognition 2020
#### Label Famous (and not-so-famous) Landmarks in Images
---

### **Description**

The [Google Landmark Recognition 2020](https://www.kaggle.com/competitions/landmark-recognition-2020/overview) on Kaggle aims to develop a machine learning model for accurate identification and classification of landmarks in images worldwide. This project's objective is to advance computer vision techniques and improve landmark recognition algorithms. Challenges include handling varying lighting, angles, and image quality, as well as large-scale datasets. We strive to develop robust models, enhance recognition accuracy, handle scalability, foster generalization to unseen landmarks, and promote innovation in the field. Successful outcomes will contribute to cutting-edge landmark recognition, benefiting applications such as travel recommendations and cultural heritage preservation.

This competition challenges Kagglers **to build models that recognize the correct landmark (if any) in a dataset of challenging test images.**

 ### Data Fields

The [Dataset](https://www.kaggle.com/competitions/landmark-recognition-2020/data) for the Google Landmark Recognition Challenge 2020 on Kaggle consists of a large collection of images from various landmarks around the world. The dataset is designed to facilitate the development and evaluation of machine learning models for landmark recognition.


**In this competition**, you are asked to take test images and recognize which landmarks (if any) are depicted in them. The training set is available in the `train/` folder, with corresponding landmark labels in `train.csv`. The test set images are listed in the `test/` folder. Each image has a `unique id`. Since there are a large number of images, each image is placed within three subfolders according to the first three characters of the `image id` (i.e. image `abcdef.jpg` is placed in `a/b/c/abcdef.jpg`).

- Files - 1590817 files
- Size - 105.52 GB
- Type - jpg, csv

In this Notebook, covers various essential aspects. It begins by importing the required libraries, followed by reading and visualizing the data. Data augmentation techniques are applied to enhance the dataset. The modeling phase includes using the EfficientNetB0 architecture, evaluating the best model, and incorporating cosine similarity calculations. Confidence scores are computed, and the DELF module is integrated for local feature extraction. Finally, reranking techniques are implemented to refine the predicted results. These steps collectively aim to develop an accurate landmark recognition model using deep learning and advanced techniques.


![Google-challenge- png](https://github.com/LavanyaMuthuraman/Google-Landmark-Recognition-2020/assets/109660074/f7c8c093-d961-4087-bb88-d6dbe5a3157a)
