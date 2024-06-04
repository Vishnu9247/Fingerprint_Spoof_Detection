# Fingerprint_Spoof_Detection

### Overview
This project focuses on distinguishing between genuine and forged fingerprints using machine learning classification algorithms. By analyzing fingerprint patterns and features, we aim to build an accurate model that can identify fraudulent prints.

### Dataset
We collected a diverse dataset of fingerprint images, including both real (genuine) and artificially generated (fake) prints. Annotations indicate the authenticity of each fingerprint. The dataset is split into training, validation, and test sets.

### Model Selection
We’ll explore various classification algorithms to find the most suitable one for this task.

### Feature Extraction
Preprocessing: We’ll normalize the fingerprint images and remove any noise or artifacts.

Feature Extraction: Extract relevant features from the fingerprint images. Common features include ridge patterns, minutiae points, and texture descriptors.

### Model Training
Data Split: We’ll divide the dataset into training , validation , and test subsets.

Model Training: Train the selected classification algorithm on the training data.

Hyperparameter Tuning: Optimize hyperparameters (e.g., kernel type, regularization strength) using cross-validation on the validation set.

### Evaluation Metrics
We’ll assess the model’s performance using the following metrics:

Accuracy: Overall correctness of predictions.

Precision: Proportion of true positive predictions among all positive predictions.

Recall (Sensitivity): Proportion of true positive predictions among all actual positive samples.

F1-score: Harmonic mean of precision and recall.
