# Data Scientist Nanodegree - Convolutional Neural Networks (CNN) - Image classification

## Project : Dog Breed Classifier

## Table of Contents

1. [Overview](#overview)
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

### Overview <a name="overview"></a>

This project uses Convolutional Neural Networks (CNNs)! In this project, I have build a pipeline to process real-world, user-supplied images. Given an image of a dog, my algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. The goal is to classify images of dogs according to their breed. The algorithm that detects humans in an image is different from the CNN that infers dog breed.

### Installation <a name="installation"></a>

This project requires Python and libraries used in Data Science and Deep Learning such as:

1. numpy
2. pandas
3. matplotlib
4. scikit-learn
5. keras

To easily check the code at the same time as the output, it is recommended to install Anaconda and Jupyter Notebook. To speed up training time, it is highly recommended to use GPU.

### Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2020 to better understand:

1. What are the most wanted languages for next year 2021 ?
2. How is total compensation (USD) correlate to developer type ?
3. Which country has the highest average total compensation (USD) ?
4. How well can we predict an individual's age ? What aspects correlate well to age ?

The full set of files related to this course are publicly available here. You can see whole analysis here.

### File Descriptions <a name="files"></a>

There is 1 notebook available here to showcase work related to the above questions. The notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title. Markdown cells were used to assist in walking through the thought process for individual steps.  

### Results<a name="results"></a>

![image](https://user-images.githubusercontent.com/88196723/145411863-9e892922-4515-4a5f-9d30-40266a4203cf.png)

The best model gives approx. 79% of accuracy. It performs well on almost dog images. The outputs for human images are also convincing.

The main findings of the code can be found at the post available [here](https://medium.com/@Shiv_Shiv/check-out-your-face-resembles-which-dog-breed-a49caaae42).

### Licensing, Authors, Acknowledgements<a name="licensing"></a>

The dataset was provided by Udacity as part of its "Data Scientist Nanodegree program". A LICENSE file is added in this repo to state clearly its licence.
