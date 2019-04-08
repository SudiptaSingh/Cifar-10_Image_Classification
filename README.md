•	Problem Statement :-
Add features like Object Classifier, random wallpaper, geo-tagging, fingerprint sensor etc. so that app usage may become more simple and 
make user experience more enjoyable. 
Object classification by using artificial neural networks (ANN),convolutional neural networks(CNN) and data augmentation through which the 
app will divide all the saved images into different categories by which the helps the user to easily find any image of a particular 
category instead searching in the whole data of images to find one.
Random wallpaper will provide the user with a random image within the category of images as provided by the user.
Fingerprint sensor to secure the data and make sure that any outsider is not using the app without the permission of the user.

•	Software/Technologies  and databases used :-

Software/Technologies:-	
	Android studio version 3.0 Beta 6
	Jupyter Notebook (Python Editor)
	TensorFlow

Databases:-
	Cifer10

Languages used:-
	Python
	Java

Concepts Used:-
	Artificial Neural Networks(ANN)
	Convolutional Neural Networks(CNN)
	Data Augmentation 

Analysis:-
Complete Accuracy Analysis of Image Classifier Algorithm on the bases of changes in basic CNN and ANN model, Data augmentation and 
iterations. Comparison is done by training our model on different values of these parameters and plotting graphs (line, bar) in between
changed values and it’s resulting accuracy. 
•	Comparisons between our work and Existing work:-
Our recent work is more inclined to wards research on  
” Neural Networks” based image classifier so  that we can  
	Train our model in a more optimized manner, implement it
in the existing project to make the experience of the gallery
app more enjoyable.

•	Algorithms/ Approach used and Implemented:-
Our Project has been divided into two parts:-
1.)	 Research oriented part in which we are trying to Analyze out Image classifier algorithm to increase it’s efficiency and implement
it in our open source app. It works as follows:-
Neural Networks (ANN and CNN) has been used to implement Image classifier. This Algorithm consist of 2 layers of “Convoluetunial layer
(Kernels=5,  depth=64 ) + Maxpooling Layer (  Kernel = 2,   Stride= 2 )”. Total iterations taken are 15000 with the batch size of 100 
Images choose randomly.
2.)	Android oriented part in which we are trying to implement the extra functionalities and try to remove bugs proposed in master 
repositories. Functionalities like automatic wallpaper download according to tags and     3D-cube image viewer.

Pre Information:-

•	System used in analysis and training of models :-

	Lenovo Y5070 	
Configuration:- 
•	Windows 10 Home Single Language 64-bit
•	Intel(R) Core(TM) i7-4710HQ CPU @ 2.50GHz
•	NVIDIA GeForce GTX 960M
•	8192MB RAM

	Lenovo G5080
Configuration:-
•	Windows 10 Home Single Language 64-bit
•	Intel(R) Core(TM) i3-5005U CPU @ 2.00GHz
•	Intel(R) HD Graphics 5500
•	8192MB RAM

	Customized Laptop
Configuration:-
•	Windows 10 Pro 64-bit
•	Intel(R) Core(TM) i5-6500 CPU @ 3.20GHz (Desktop Processor)
•	NVIDIA GeForce GTX 970M (Desktop Graphics card)
•	8192MB RAM
•	Parameters Considered and there default values:- 
	Number of iterations ( 15000 )
	Size of feature detector ( Kernal = 5 )
	Maxpool Kernal and Stride ( Kernal = 2, Stride = 2 )
	Crop Images (24 )
	Batch Size ( 100 )

Analysis:-
i.	Iterations v/s Accuracy :-
(No. of Iterations 10-30000)
  
ii.	Feature Detector v/s Accuracy :-
( 4, 5, 6 ,7, 8 )
  
iii.	Crop Images v/s Accuracy :-
(10, 15, 20, 24, 30 )
  
iv.	Batch Size v/s Accuracy :-
(200, 500, 1000, 1500 )
 
v.	{Conv.(5,64) + Maxpooling(2,2)}x2 + {Conv.(5,32) + Maxpooling(3,3)} :-

Crop size = 24
Accuracyachieved = 65.9%
Time = 50min 43sec
No. of epochs = 15000
Batch Size = 100 

vi.	{Conv.(5,64) + Maxpooling(2,2)}x3 :-

Crop size = 24
Accuracyachieved = 68.2%
Time = 44min 46sec
No. of epochs = 15000
Batch Size = 100 

vii.	{Conv.(5,64) + Maxpooling(2,2)}x2
{F.C. Hidden Layers Neurons – (256-128-64)}:-

Crop size = 24
Accuracy achieved = 68.8%
Time = 38min 34sec
No. of epochs = 15000
Batch Size = 100 

viii.	*{Conv.(5,64) + Maxpooling(2,2)}x3
{F.C. Hidden Layers Neurons –                        (256-128-64-32)}:-

Crop size = 30
Accuracy achieved = 73.9%
Time = 38min 34sec
No. of epochs = 15000
Batch Size = 100



ix.	*{Conv.(5,64) + Maxpooling(2,2)}x3
{F.C. Hidden Layers Neurons –                        (256-128-64-32)}:-

Crop size = 30
Accuracy achieved = 75.8%
Time = 38min 34sec
No. of epochs = 30000
Batch Size = 100

*Maximum Accuracy achieved till now

x.	{Conv.(5,128) + Maxpooling(2,2)} +
{Conv.(5,64) + Maxpooling(2,2)} +
{Maxpooling(2,2)} :-

Crop size = 24
Accuracy achieved = 69.2%
Time = 44min 26sec
No. of epochs = 15000
Batch Size = 100
