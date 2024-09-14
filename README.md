# CNN H&E Metastasis detection
## Overview
The dataset we are working with consists of a subset of H&E (Hematoxylin and Eosin) stained pathological scans of lymph nodes. H&E staining is a widely used technique in histology that highlights cellular structures and nuclei, providing detailed insights into tissue architecture. This staining method is particularly useful for visualizing the presence of cancer cells and evaluating the extent of metastasis, as it can clearly delineate tumor tissues from normal structures.

Lymph node scans play a crucial role in cancer diagnosis, as these nodes are often the first site where cancer cells spread from primary tumors. The presence of metastases in lymph nodes can indicate that cancer has begun to disseminate to other organs, making early and accurate detection vital for effective treatment planning.

In this project, we are addressing a binary classification problem. Each scan in the dataset can be categorized into one of two classes: it either contains metastatic tumor cells or it is non-cancerous. The primary objective is to develop a Convolutional Neural Network (CNN) model capable of distinguishing between these two categories with high accuracy. By training the CNN on these annotated H&E scans, we aim to create a predictive tool that can assist pathologists in identifying tumor presence more efficiently and reliably.

The dataset for this project was obtained from a Kaggle competition, which is a common platform for accessing diverse datasets and participating in data science challenges. The competition setting provides an additional layer of validation, as models are often evaluated against a hidden test set to ensure generalizability and robustness. This not only offers a practical context for the project but also aligns with current best practices in machine learning and medical image analysis.

## Files
Please refer to the Jupyter Notebook for the codes and visualization of the project.

This is the performance of my model with the test data on Kaggle
<img width="977" alt="Test_score" src="https://github.com/user-attachments/assets/30e80e98-772f-4ad1-9357-ef1f311df65b">
