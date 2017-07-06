#**Traffic Sign Recognition** 



The Follwing things were performed in this project:-
    1.The Datasets of traffic Signs where downloaded and extracted to requisite place in  the directory.
    2.Then Data was load in the form of training,test and validation sets.
    3.In next step I counted number of examples and classes in the data sets along with number of shape of the training sets.
    4.In next step I loaded displayed some training data sets.
    5.Then I reshuffled the training sets data
    6.Created Lenet model archtecture consisting of convolution network,relu and maxpool and then flattening the layer.
    7.Then we used tensor flow to learn and check the accuracy of the leNet archtecture.
    8.After Validating with test sets.I downloaded some traffic sign pictures to check the accuracy on this images that comes out to be 93.33%




**Steps Used in this Project**

The goals / steps of this project are the following:
* Downloaded the Data set into the directory
* Load the data set 
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to check predictions accuracy on new images
* Summarize the results with a written report


[//]: # (Image References)

## Rubric Points
| CRITERIA			        |    MEETS SPECIFICATIONS       					| 
|:---------------------:|:---------------------------------------------:| 
| Submission Files      		| Submission files includes ipynb notebook,html file and writeup.md   									| 
| Dataset Summary    			| Provided in the notebook  										|
| Exploratory Visualization					| Step Performed in the notebook											|
| Preprocessing	      		| Explained 					 				|
| Model Architecture			| Performed in the notebook      							|
| Model Training			| Performed Using Tensorflow      							|
| Performance on New Images	| Performed in the notebook   							|




---
###Writeup / README
Provided in the writeup template

###Data Set Summary & Exploration

I used the pandas library to calculate summary statistics of the traffic
signs data set:

* The size of training set is =34799
* The size of the validation set is =12630
* The size of test set is =4410
* The shape of a traffic sign image is =(32,32,3)
* The number of unique classes/labels in the data set is = 43
