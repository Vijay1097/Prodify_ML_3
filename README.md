# Dog and Cat Image Classification - Task 3

This repository contains my submission for **Task 3** of the internship at **Prodigy InfoTech**: **Dog vs Cat Image Classification using Machine Learning**.

## Objective
To build an image classification model that can accurately distinguish between images of dogs and cats using a supervised machine learning algorithm.

## Technologies Used
- Python
- NumPy
- Pandas
- OpenCV (for image loading and preprocessing)
- Scikit-learn (for SVM model and evaluation metrics)
- Matplotlib (for visualization)

## Dataset
A labeled collection of cat and dog images. The dataset was cleaned, resized, converted to grayscale, flattened, and split into training and testing sets.

## Workflow
1. **Data Loading** – Loaded images of dogs and cats using OpenCV.
2. **Preprocessing** – 
   - Resized images to a fixed size  
   - Converted images to grayscale  
   - Flattened image arrays for model input  
   - Encoded labels as binary (cat = 0, dog = 1)
3. **Model Building** – Built and trained an SVM (Support Vector Machine) classifier.
4. **Model Evaluation** – Evaluated using accuracy score and confusion matrix.
5. **Prediction** – Predicted class (dog or cat) for new input images.

## Output Visualizations

### Output 1: Sample Prediction  
![Output 1](https://github.com/Vijay1097/Prodify_ML_3/raw/main/output.png)

### Output 2: Classified Image (Dog)  
![Output 2](https://github.com/Vijay1097/Prodify_ML_3/raw/main/Dog%20output.png)

## Directory Structure
