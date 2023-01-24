# Face Recognition Using Unlabeled Data!

This Project has been created in a group. All the group members information are mentioned below table.

#### Group Members
| Student ID | Name | Email Address |
| --- | --- | --- |
| 301167516 | Abhi Patel | apate853@my.centennialcollege.ca |
| 301146236 | Jiya Kelawala | jkelawal@my.centennialcollege.ca|

Team was approached by a law enforcement security company that would like to incorporate facial recognition and identification into their system. Company has provided the team with the umist_cropped.mat dataset to train Machine Learning system.
Dataset has images of 20 different person. Images of each person contains different profile of face of that person. Total number of images for each person is different. 
Goal: Using clustering techniques, incorporate facial recognition and identification of different images.

## Required Libraries

The following libraries are required to be installed in the machine to run the python scripts. 
pip3 install numpy pandas tensorflow matplotlib scikit-learn keras 

## Main steps taken:
1) Load data
2) Increase data using autoencoder to make stratified datasets
3) scaling data
4) Shuffling data in-folder(shuffling images among the one person images)
5) Create stratified train, validation, test data
6) Shuffle all 3 datasets again out-folder (shuffling across whole dataset that includes all persons images)
7) Implementing different cluster techniques
8) Training and evaluating ANN classfier model
9) Fine-tuning Hyper parameters of ANN model - RandomizedSearchCV
10) Predicting and showing the results

Data Augmentation -> Autoencoder

Dimension Reduction -> PCA (Principle Component Analysis)

We have tried 3 clustering Techniques
1) AHC - agglomerative hierarchical clustering
2) K-means clustering
3) GMM - Gaussian Mixture Model

Prediction with ML Model -> ANN (Artificial Neural Network)

Fine Tuning -> RandomizedSearchCV

Performance Measures -> Precision, Recall and Accuracy

## Run file
unsupervised_project.py


