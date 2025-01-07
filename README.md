Task 1: Age Detection Using Deep Learning

Name: Abhay Singh

Welcome to the Age Detection project! This project is designed to predict the age of a person based on facial images using deep learning. The model is fine-tuned using MobileNetV2, a lightweight neural network architecture, and trained on a custom dataset.

Dataset

The dataset consists of facial images where each file name includes the age of the individual. For example, a file named 25_image1.jpg corresponds to an individual aged 25. The dataset is preprocessed and split into training and testing subsets.

Dataset Link: (https://drive.google.com/drive/folders/1DCk9ZfbuPW5saRBU2gcALQ6qgfT8FRJP?usp=sharing)

Features

1. Data Augmentation: To enhance model generalization, data augmentation techniques like rotation, zoom, and horizontal flipping are applied.

2. Pre-trained MobileNetV2 Model: Used as the base model, fine-tuned for regression tasks.

3. Custom Data Generators: Efficient loading and preprocessing of images.

4. Output to CSV: Predicted ages are saved to a CSV file for easy reference.

5. Visual Analysis: Training history is visualized using loss and validation loss plots.

