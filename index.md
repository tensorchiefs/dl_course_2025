
# Deep Learning (CAS machine intelligence, 2025) 

This course in deep learning focuses on practical aspects of deep learning. We therefore provide jupyter notebooks ([complete overview of all notebooks](https://github.com/tensorchiefs/dl_course_2025/tree/master/notebooks) used in the course). 

For doing the hands-on part we recommend to use google colab <a href="https://colab.research.google.com/"><img src="https://colab.research.google.com/img/colab_favicon_256px.png" width="20"></a> (you might need a google account) an internet connections is also needed. If you want to do it without internet connection on your own computer you can install anaconda ([details and installation instruction](anaconda.md)). Please note that we are not experts in anaconda and thus can only give limited support.

To easily follow the course please make sure that you are familiar with the some [basic math and python skills](prerequistites.md).  

## Info for the projects
You can join together in small groups and choose a topic for your DL project. You should prepare a poster and a spotlight talk (5 minutes) which you will present on the last course day. To get some hints how to create a good poster you can check out the links that are provided in <a href="https://www.dropbox.com/s/u1f6mqk4pc3uhxe/poster-guidelines.pdf?dl=1">poster_guidelines.pdf</a> 

If you need free GPU resources, we might want to follow the [instructions how to use google colab](co.md).  



Examples for projects from previous versions the DL course:
  [2018, 2019](projects.md)
  [2020](https://docs.google.com/spreadsheets/d/1NXinRQMifg_QNQs1fyn5HeiZNRnTGnIy1W7-ij-jQhg/edit?usp=sharing)
  [2021](https://docs.google.com/spreadsheets/d/18VFrPbKq3YSOg8Ebc1q1wGgkfgaWl7IkcCClGEDGj6Q/edit#gid=0)
  [2022](https://docs.google.com/spreadsheets/d/1TZf5hKekzOlBC7J0-EAltGOMTuZyrDhHu3ANve0q6H4/edit#gid=0)
  [2023](https://docs.google.com/spreadsheets/d/1d1y-Qf9OW7Vg30WzWwCckYPBMyRcg-d-qLG_lA0Z5jk/edit#gid=0)
  [2024](https://docs.google.com/spreadsheets/d/1drTY6DA2R5QQYk8mRvcPFx-lW98aOGLgppkMMweHZPM/edit#gid=0)

Open Datasets: [papers with code](https://paperswithcode.com/datasets), [kaggle](https://www.kaggle.com/datasets)

Hints: [Upload data to colab](https://colab.research.google.com/notebooks/io.ipynb) , [keras with your own images](https://keras.io/api/data_loading/)

 
**Fill in the Title and the Topic of your Projects until End of Week 5 [here](https://docs.google.com/spreadsheets/d/1dwH1f1-2veH2o9Gv6crmQHfVsSKZto-dDopfxTUbzy8/edit?gid=0#gid=0)**

## Other resources 
We took inspiration (and sometimes slides / figures) from the following resources.

* Probabilistic Deep Learning (DL-Book) [Probabilistic Deep Learning](https://www.manning.com/books/probabilistic-deep-learning?a_aid=probabilistic_deep_learning&a_bid=78e55885). This book is written by us the tensorchiefs and covers the increasingly popular probabilistic approach to deep learning.

* Deep Learning Book (DL-Book) [http://www.deeplearningbook.org/](http://www.deeplearningbook.org/). This is a quite comprehensive book which goes far beyond the scope of this course. 

* Convolutional Neural Networks for Visual Recognition [http://cs231n.stanford.edu/](http://cs231n.stanford.edu/), has additional material and [youtube videos of the lectures](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC). While the focus is on computer vision, it also treats other topics such as optimization, backpropagation and RNNs. Lecture notes can be found at [http://cs231n.github.io/](http://cs231n.github.io/).


* Math concept videos at [3blue1brown](https://www.youtube.com/@3blue1brown)

## Dates & Topics
The course is split in 8 sessions, each 4 lectures long. Topics might be adapted during the course

| Day  |      Date    |      Time    |   Topic
|:--------:|:--------------|:---------|:---------------|
| 1        | 15.04.2025 | 09:00-12:30 |  Introduction to Deep Learning & Keras, first NNs |
| -        | 21.04.2025 |-            | FRÜHLINGS-FERIEN                                  |
| -        | 28.04.2025 |-            | FRÜHLINGS-FERIEN                                  |
| 2        | 06.05.2025 | 09:00-12:30 | Loss, Optimization, Regression, Classification    |
| 3        | 13.05.2025 | 09:00-12:30 | Computer vision, CNN-archictecture  |
| 4        | 20.05.2025 | 09:00-12:30 | DL in practice, pretrained (foundation) models  | 
| 5        | 27.05.2025 | 09:00-12:30 | Model evaluation, baselines, xAI, troubleshooting  |
| 6        | 03.06.2025 | 09:00-12:30 | Generative Models, Transformer-architecture   |
| 7        | 10.06.2025 | 09:00-12:30 | Vision Transformer  |
| 8        | 17.06.2025 | 09:00-12:30 | Projects, deep Ensembling   |




## Provided Material 
- Day 1
  - Slides:
    - [01_DL_Introduction](https://github.com/tensorchiefs/dl_course_2025/blob/master/slides/01_2025_Introduction.pdf)
  - Additional Material: 
    - [Network Playground](https://playground.tensorflow.org/)
  - Exercises:
    - [00_Checking_Correct_Installation_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/00_Checking_Correct_Installation_keras_torch.ipynb) 
    - [01_simple_forward_pass_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/01_simple_forward_pass_keras_torch.ipynb) 
- Day 2
  - Slides:
    - [02_Regression_Classification_Loss](https://github.com/tensorchiefs/dl_course_2025/blob/master/slides/02_2025_loss_presented.pdf)    
  - Exercises:
     - [02_fcnn_with_banknote_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/02_fcnn_with_banknote_keras_torch.ipynb)
     - [02_custom_loss.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/02_custom_loss.ipynb)
- Day 3
  - Slides:
     - [03_CNN_intro](https://github.com/tensorchiefs/dl_course_2025/blob/master/slides/03_2025_CNN_presented.pdf)
  - Additional Material:
    - [What is a Kernel (Interactive) ](https://setosa.io/ev/image-kernels/)
    
     
  - Exercises:
    - [03_fcnn_mnist_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/03_fcnn_mnist_keras_torch.ipynb)

        **optional** (what happens if we shuffle the image?): [04_fcnn_mnist_shuffled_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/04_fcnn_mnist_shuffled_keras_torch.ipynb)
      
    - [05_cnn_edge_lover_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/05_cnn_edge_lover_keras_torch.ipynb)
    
       **optional** (what happens if we shuffle the image?):  [06_cnn_mnist_shuffled_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/06_cnn_mnist_shuffled_keras_torch.ipynb)
    
- Day 4
  - Slides:
     - [04_CNN_in_practice](https://github.com/tensorchiefs/dl_course_2025/blob/master/slides/04_2025_CNN_in_practice.pdf) 
  - Exercises:
     - [07_early_stopping_and_modelweights.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/07_early_stopping_and_modelweights.ipynb)
     - [07_cifar10_tricks_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/07_cifar10_tricks_keras_torch.ipynb)
     - [08_classification_transfer_learning_few_labels_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/08_classification_transfer_learning_few_labels_keras_torch.ipynb)    

- Day 5
  - Slides:
     - [05_2025_CNN_eval_xAI](https://github.com/tensorchiefs/dl_course_2025/blob/master/slides/05_2025_CNN_eval_xAI.pdf) 
  - Exercises:
     - [15_faces_regression_keras_torch.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/15_faces_regression_keras_torch.ipynb)
   - Additional Excercise (caution this is mostly Tensorflow):
      - [08_gradcam_and_occlusion_keras_TENSORFLOW.ipynb](https://github.com/tensorchiefs/dl_course_2025/blob/master/notebooks/08_gradcam_and_occlusion_keras_TENSORFLOW.ipynb)
