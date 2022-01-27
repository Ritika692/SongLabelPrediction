# SongLabelPrediction
Using the MLEnd dataset, I  built a model that predicts the song label of a short audio segment and used SVM model for getting accuracy.
2. Problem Formulation

A machine learning problem that takes as an input a Potter or StarWars audio segments and predicts its song label (either Potter or StarWars)

The interesting  thing about it is the features extracted from the audio signals of Potter and StarWars audio signals and modelling the features through SVM classifier to predict the audio labels.(Potter or StarWars)
3. Machine Learning pipeline


Input :
For the input we have taken "Humming or Whistling" Starwars or Potter audio files.

Output:
For the output we would be gettting "StarWars" or "Potter" song labels 

Intermediate Stages:

1. Environment Setup: Loading the required libraries and accessing to drive
2. Data Accessing from Drive
3. Exploratory Data Analysis

Finding the number of files in the google drive "Mini_Project" folder.

Displaying the various(5) audio files

Getting the name of the audio files
4. Extracted Features:

Power.

Pitch mean.

Pitch standard deviation.

Fraction of voiced region.

5. Building training and testing data

6. Modelling 

7. Finding Accuracy

8. Finding the best value of C and gamma value for SVC

9. Displaying the confusion matrix

10. Displaying the Classification Report

11. Plotting heatmap

12. Predict the value of the validation accuracy as a function of C
