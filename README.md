# FashionImageClassifier

🚀 Project Highlight: Fashion MNIST Classification using SVM and HOG Features 🧵

🔍 Objective: Build a robust image classification model for the Fashion MNIST dataset using Support Vector Machine (SVM) with Histogram of Oriented Gradients (HOG) features.

Key Features and Steps:

Data Preprocessing:

Loaded the Fashion MNIST dataset containing 60,000 training and 10,000 test images.
Normalized the pixel values for consistent and efficient model training.
Feature Extraction:

Utilized HOG (Histogram of Oriented Gradients) to extract important features from the images.
Enhanced the feature set by adding a channel dimension to the images.
Model Training:

Trained an SVM classifier with a linear kernel using the extracted HOG features.
Achieved a high training accuracy, ensuring the model's robustness.
Model Evaluation:

Evaluated the model on the test set to check its performance.
Visualized the true vs. predicted labels to interpret the results better.
Visualization:

Plotted the initial and predicted images for a better understanding of model performance.
🌟 Technologies Used:

Libraries: TensorFlow, OpenCV, Scikit-learn, Matplotlib, NumPy
Techniques: SVM, HOG, Data Normalization, Image Reshaping
