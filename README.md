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

