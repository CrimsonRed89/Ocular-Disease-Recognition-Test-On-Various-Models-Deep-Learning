# Ocular Disease Recognition (ODIR) - Model Performance Evaluation
This repository showcases a comprehensive evaluation of various deep learning models on the Ocular Disease Intelligent Recognition (ODIR) dataset. The project includes a custom-built Deep Neural Network (DNN) designed to offer a comparative analysis against well-known architectures such as VGG, ResNet, and Inception. The primary objective is to assess the accuracy and effectiveness of these models in diagnosing multiple ocular diseases from retinal images.

# Dataset
The dataset used in this project is the Ocular Disease Recognition (ODIR) dataset, consisting of 5,000 retinal images labeled with conditions like diabetic retinopathy, glaucoma, and age-related macular degeneration. The dataset is directly imported from Kaggle. You can explore and download it here: https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k

# Implementation
The project is implemented in a single Python file, which includes the following steps:

### Data Loading & Preprocessing:
The ODIR dataset is loaded and preprocessed to ensure it's suitable for model training and evaluation.
### Model Selection: 
Standard deep learning models such as VGG16, ResNet50, EfficientNet, and InceptionV3 are implemented and trained on the dataset.
### Custom DNN Architecture: 
A custom Deep Neural Network (DNN) is designed and trained to benchmark its performance against the established models.
### Performance Evaluation: 
The accuracy, loss, and other relevant metrics are calculated for each model. The results are visualized through confusion matrices, ROC curves, and other tools to facilitate a clear comparison.
### Prediction Visualization: 
The true labels and the model’s predictions are compared to assess how well each model generalizes to unseen data.

# Results
The results demonstrate that the custom DNN performs competitively with the established models, achieving high accuracy in predicting ocular diseases. The analysis includes a detailed comparison of the models, highlighting the strengths and weaknesses of each approach. The single file provided in the repository contains all the necessary code to reproduce these results.

# How to Use
### Clone the Repository: 
Start by cloning this repository to your local machine.
### Dataset Access: 
Ensure you have access to the ODIR dataset on Kaggle. You can either download it manually or use Kaggle’s API to import it directly into your workspace.
### Run the Code: 
Execute the provided Python file. It will automatically handle the data loading, preprocessing, model training, and evaluation.
### Analyze Results: 
After running the file, you will be able to review the model performances, including accuracy, precision, recall, F1 scores, and more.

# Conclusion
This project serves as a benchmark study for ODIR prediction using both pre-existing models and a custom DNN. It provides insights into the capabilities of deep learning for medical image classification, particularly in the field of ocular disease recognition.
