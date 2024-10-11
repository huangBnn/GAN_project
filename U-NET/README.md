### Goals
In this notebook, you're going to implement a U-Net for a biomedical imaging segmentation task. Specifically, you're going to be labeling neurons, so one might call this a neural neural network! ;) 

Note that this is not a GAN, generative model, or unsupervised learning task. This is a supervised learning task, so there's only one correct answer (like a classifier!) You will see how this component underlies the Generator component of Pix2Pix in the next notebook this week.

### Learning Objectives
1.   Implement your own U-Net.
2.   Observe your U-Net's performance on a challenging segmentation task.

## Getting Started
You will start by importing libraries, defining a visualization function, and getting the neural dataset that you will be using.

#### Dataset
For this notebook, you will be using a dataset of electron microscopy
images and segmentation data. The information about the dataset you'll be using can be found [here](https://www.ini.uzh.ch/~acardona/data.html)! 

> Arganda-Carreras et al. "Crowdsourcing the creation of image
segmentation algorithms for connectomics". Front. Neuroanat. 2015. https://www.frontiersin.org/articles/10.3389/fnana.2015.00142/full

![dataset example](Neuraldatasetexample.png)


## training: 

Epoch 137: Step 1100: U-Net loss: 0.09717568010091782

feature:

![image](https://github.com/user-attachments/assets/e468a794-c92d-4c7c-8b07-54af99638164)

target:

![image](https://github.com/user-attachments/assets/f7333ff1-264d-41ad-80d4-be79623fa5a9)

predict:

![image](https://github.com/user-attachments/assets/b0640b00-399d-4ffc-95ba-84d643205353)

===========================================================================================

at very beginning

Epoch 2: Step 20: U-Net loss: 0.5142393708229065

feature:

![image](https://github.com/user-attachments/assets/d9a4829a-ed34-4d05-8f96-c0d4baac8af3)

target:

![image](https://github.com/user-attachments/assets/259a0d04-a8f5-4076-ba4d-e39d09eb740b)

predict:

![image](https://github.com/user-attachments/assets/7e7f3ef9-2e3f-4a65-9875-12f4739eebdc)
