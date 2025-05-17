Handwritten Digit Recognition System
This project is about recognizing handwritten digits (0 to 9) using machine learning. We used a small version of the MNIST dataset provided by Scikit-learn and built models to classify the digits based on their image features.

Project Overview
The project includes:
•	Data loading and visualization
•	Data preprocessing
•	Training three different machine learning models
•	Evaluating and comparing model performance
•	Visualizing confusion matrices and ROC curves

Dataset
•	Source: load_digits() from Scikit-learn
•	Contains 1797 8x8 images of digits
•	Each image is represented as a flattened 64-dimensional feature vector

Technologies and Libraries
•	Python
•	Scikit-learn (sklearn)
•	Pandas
•	Matplotlib
•	Random
•	Time

Steps Performed
1. Data Visualization
•	Displayed the first 100 handwritten digit images in a 10x10 grid.
2. Data Preprocessing
•	Loaded image data and labels from the dataset.
•	Split the dataset into training (0–1500) and testing (1501–1796) subsets.
•	Binarized the target labels to enable ROC curve generation for multiclass classification.
3. Model Building
Trained and tested the following classifiers:
•	Logistic Regression
•	Random Forest Classifier
•	Decision Tree Classifier
4. Model Evaluation
Used the following metrics for evaluation:
•	Accuracy Score
•	ROC AUC Score
•	Classification Report
•	Confusion Matrix Display
•	ROC Curve Display
5. Visualizations
•	Confusion Matrices for each model
•	ROC Curves to visualize multiclass performance
•	Initial data visualization of digit images

Results
All three models were evaluated and compared using confusion matrices and ROC curves. The project provides insights into how different classifiers perform on image-based multiclass classification tasks.

![image](https://github.com/user-attachments/assets/23db7f7d-ea46-4fc1-80d8-22b0cbcb496f)
