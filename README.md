This repository contains code for building and evaluating an image classifier using Support Vector Machine (SVM) in Python. The classifier is trained to classify images into two categories: "empty" and "not_empty".


The main components of this project include:

Data Preparation: The input data is located in the data/clf-data directory. Images from each category are loaded, resized to 15x15 pixels, and flattened to create the feature vectors used for training the classifier.

Model Training: A Support Vector Machine (SVM) classifier is trained using the Scikit-learn library. Grid search with cross-validation is used to find the best hyperparameters (gamma and C) for the SVM.

Model Evaluation: The trained classifier is evaluated on a separate test set to measure its performance. Accuracy score is used as the evaluation metric.

Model Persistence: The best performing classifier is serialized using Python's pickle module and saved as model.p for future use.

Link for Data : https://drive.google.com/drive/folders/1jovc7oBMFV1DutrijBFDbEMIO7fWwh5o
