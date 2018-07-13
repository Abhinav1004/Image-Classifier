## Cifar10 Image Classification Project.

In this project, we classify images from the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. The dataset consists of airplanes, dogs, cats, and other objects. Here, we preprocessed the data, then train a convolutional neural network on all the samples. We normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, we inspect their predictions on the sample images.	+In this project, we classify images from the CIFAR-10 dataset. The dataset consists of airplanes, dogs, cats, and other objects. Here, we preprocessed the data, then train a convolutional neural network on all the samples. We normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, we inspect their predictions on the sample images.  
 	 
![](images/cifar1.jpg)	![Cifar10][image-cifar10]
 	 
## Software Requirements
	
You only need to install [Conda](https://conda.io/docs/install/quick.html) and run the following commands:
```
conda env create -f ud-im-classification.yml
source activate ud-im-classification
```
You can open the solution by simply:
```
jupyter notebook dlnd_image_classification.ipynb 
```
## Installation 

1.Install [Anaconda](https://www.anaconda.com/download/#linux)

2.Download or clone this github repository 	
  	
3.Launch jupyter notebok within the file containing `image_classification.iypynb` file	

4.Run the cells to train and execute the model. 	
  	
## Cifar Data Set	
 It contains images of the various objects and goal of the model is to identify the objects from this data set	
![](images/cifar10.png)	
  	
## Final Result	

![](images/final_prediction.png)
