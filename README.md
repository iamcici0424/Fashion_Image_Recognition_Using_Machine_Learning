## Fashion Image Recognition Using Machine Learning

**Term** : Spring 2019

**Group members**:

+ Cici Chen cc4291@columbia.edu
+ Mehak Khara mk4196@columbia.edu
+ Xueyan Zou xueyan.z@columbia.edu

**Goal**: 

The project will focus on an image recognition problem, and we will construct a variety of machine learning models with the goal of generating predictive classifications. Our purpose is to get as accurate predictive classifications of testing sets as possible, while limiting the size of training rows as well as computing time. We constructed points reflect these three features of our models, and the goal is to obtain lower points - lower error, less time and smaller sample size.


### Introduction:
Our project is mainly about image recognition using data from [MNIST Fashion Database](https://github.com/zalandoresearch/fashion-mnist). 

The dataset collected a large number of images for different types of apparel. Each image is divided into small squares called pixels of equal area. Within each pixel, a brightness measurement was recorded in grayscale. The brightness values range from 0 (white) to 255 (black). Training data (*60,000 rows*) and testing data (*10,000 rows*) are all composed of information about 49 pixels of clothing pictures along with their labels. 

Our team trained 10 different machine learning models to generate predictive classifications of testing sets. We built these 10 models using 9 sample training sets with sizes 500, 1000 and 2000, and each of the size is randomly sampled from the whole training set for three times.
