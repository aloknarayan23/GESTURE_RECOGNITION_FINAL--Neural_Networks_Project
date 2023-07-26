# GESTURE RECOGNITION-Neural Networks Project
Build neural network models which identify gestures to control smart TV.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## General Information
- Problem:
		Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions.
		You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 
		The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
			Thumbs up:  Increase the volume
			Thumbs down: Decrease the volume
			Left swipe: 'Jump' backwards 10 seconds
			Right swipe: 'Jump' forward 10 seconds  
			Stop: Pause the movie

	
- Understanding DataSet : 
		The training data consists of a few hundred videos categorised into one of the five classes.
		Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images).
		These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 
		Note that all images in a particular video subfolder have the same dimensions but different videos may have different dimensions.
		Specifically, videos have two types of dimensions - either 360x360 or 120x160 (depending on the webcam used to record the videos).
		Hence, you will need to do some pre-processing to standardise the videos.


## Conclusions
Model built using Transfer Learning with GRU is working best to recognise gesture.
Here we achieved a good training accuracy of 99.40% and the validation accuracy of 99.0%.


## Technologies Used
Language : Python 

Libraries : 
      - pandas
      - numpy
      - matplotlib.pyplot
      - warnings
	  - cv2
	  - imageio
	  - imread
	  - skimage.transform
	  - resize
	  - random
	  

## Contact
Created by :
        Alok Narayan(https://github.com/aloknarayan23)
		            - feel free to contact me!