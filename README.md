# plant-disease-detection

> improve Yolov5 by using CBAM, INVOLUTION AND SODH BLOCK.<br>
> Data take in kaggle, for mask using labelimg.<br>

## Problem Summary:
### 1. Objective: To detect and classify plant diseases in order to provide timely preventive and treatment measures, thereby improving crop yield and quality.

### 2. Data: Images of plants or plant leaves (with or without disease) are collected as training data. This data needs to be labeled, meaning each image must be associated with information about the type of disease or the plant’s health condition.

### 3. Key Steps:

(a) Data Preprocessing: Cleaning the image data, cropping, resizing, and augmenting the images to create a diverse dataset.

(b)Feature Extraction: Using manual feature extraction techniques (such as SIFT, HOG) or deep learning models to automatically learn features from the images (using Convolutional Neural Networks - CNN).

(c) Model Building: Training machine learning models (such as SVM, Decision Trees) or deep learning models (like CNN) to classify plant images based on their disease status.

(d) Model Evaluation: Using metrics such as accuracy, F1-score, precision, and recall to assess the model's performance on test datasets.

### 4. Applications: This problem can be applied in smart agriculture systems, where mobile devices or drones capture plant images and detect diseases in real-time.

### 5.Challenges:

* Data can be noisy due to varying lighting conditions, camera angles, or image quality.
* Similar symptoms across different diseases may complicate the classification process.
* Lack of data on rare or newly emerging plant diseases.
* The Plant Disease Detection problem plays a crucial role in precision agriculture, helping to minimize crop losses and efficiently utilize resources.
