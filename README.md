# Pneumonia_prediction_final_project
Final project of the Big data course in Computational Biology at the Universidad Politécnica de Madrid carried out by Cristina Junos Nathan (nathanjunod99@gmail.com), Piñeres Laura (lv.pineres@alumnos.upm.es) and Rodriguez Alejandro (alejandrorodriguezsancho1@gmail.com).

We developed a model to predict whether the provided X-ray images found in the dataset https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia show pneumonia or not. Pneumonia is one of the most common acute lung infections that causes inflammation and can have serious consequences for children and the elderly.

Initialize we import kaggel hub and kaggle api next to all the needed packages and libraries, the dataset onsist of 3 folder whit images for training, validations and testing. We compared the performance of different models, including Logistic Regression, Random Forest, Gradient-Boosted Trees (GBT), and Support Vector Machines (SVM), to achieve this we converted the label string to numeric values in order to convert the feature matrix into denseVectors for compatibility with Pyspark MLlib.

Our accuracy results were 0.77 for Logistic Regression, 0.74 for Random Forest, 0.72 for GBT and 0.79 for SVM. Despite the higher accuracy, a finer tuning can be applied to the higher accuracy model as an optimisation, including a better splitting of the dataset considering that the splitting already provided shows an imbalance between the folders.

