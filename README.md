# Mailware_decetion_using_ML
## Problem Statement
we are going to build your own malware detection system. Here you are going to use only Windows executables. You are required to use the python utility pefile and linux command line utility strings to extract the static features from each PE file. Setup: Since the dataset contains malware executables, don’t try to open the samples in the dataset. Set up an Ubuntu virtual machine (higher than 16.04) and write the python code for the below. Perform the below tasks to implement the malware detection model.

1. Download the dataset given as zipped file “malware_dataset.zip”. The dataset consists of 3 folders ‘malware’ with 443 samples, ‘benignware’ with 400 samples and ‘testdata’ with 50 samples

2. Extract static features from each benign and malicious executable using python utility pefile and linux command line utility strings to represent the sample as an array of numbers. Assign the label as ‘1’ for malware and ‘0’ for benignware. This step also includes research to design good features that will help your machine learning system make accurate inferences. (Maximum number of features: 50)

3. Split dataset into non-overlapping training and test sets, in which the training set consists of 70% of the data (an arbitrarily chosen proportion) and the test set consists of the remaining 30%.4. Train the below 2 machine learning classifiers to recognize malware using the features we have extracted. Use the inbuilt functions from sklearn for implementing the models and calculating metrics  K-Nearest Neighbors  Random Forest

4. Test your model and calculate the prediction accuracy, false-positive rate and confusion matrix.

5. Predict whether the executables in the dataset folder ‘testdata’ is malware or benignware and write the results to a csv file in the name “testlabel.csv”. Format is given below. Mention ‘1’ in “Category” column if file is malware, else 0.


