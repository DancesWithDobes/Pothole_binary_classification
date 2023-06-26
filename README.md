# Pothole Image Binary Classification

### Link to the Colab Notebook:

https://colab.research.google.com/drive/1IjFBeUM7IEkt-eBMuvvymn9-GPX7B2W0?usp=sharing


This project aims to classify images as either pothole or normal (non-pothole) using deep learning techniques. It utilizes the ResNet-50 architecture and employs the PyTorch library for implementation.




# Introduction
Potholes are a common road hazard that can lead to accidents and damage to vehicles. This project aims to automatically detect if a pothole is located in an image using deep learning techniques. By training a binary classification model, the system can distinguish between images containing potholes and those without.






### To run this project, you'll need to have Python 3 and the following dependencies installed:

torch
torchvision
scikit-learn
matplotlib

You can install these dependencies by running the following command:

```pip install torch torchvision scikit-learn matplotlib```




# Model Training
The model used in this project is based on the ResNet-50 architecture, with the last fully connected layer modified to fit the binary classification task. The model is trained using the Adam optimizer and cross-entropy loss. The training progress is monitored using the validation set, and early stopping is employed if the validation loss does not improve for a certain number of epochs.

# Evaluation Metrics
After training the model, several evaluation metrics are calculated using the test set:

**Accuracy:** The proportion of correctly classified images.

**Specificity:** The ability to correctly identify normal images.

**Average Precision:** The average precision-recall score.

**AUC-ROC:** The area under the receiver operating characteristic curve.

**Confusion Matrix:** A visual representation of the classification results.

**Precision-Recall Curve:** A plot of precision vs. recall.

**ROC Curve:** A plot of the true positive rate vs. the false positive rate.


(Note to potential employeers / interviewers.. it may be easier to use the link in my resume to run the file directly in my colab)
