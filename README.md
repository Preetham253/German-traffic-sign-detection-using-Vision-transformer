# German-traffic-sign-detection-using-Vision-transformer
This project focuses on the classification of German traffic signs using two advanced deep learning models: ResNet-18 and Vision Transformer (ViT). The aim is to compare their performance in terms of accuracy and other metrics, as well as to visualize attention maps to understand the focus areas of the models during prediction.
# Project Structure
Data Preparation: Loading and preprocessing the German Traffic Sign Recognition Benchmark (GTSRB) dataset.
Model Implementation: Implementing ResNet-18 and Vision Transformer (ViT) for traffic sign classification.
Training and Evaluation: Training both models on the dataset, evaluating their performance, and comparing results.
Attention Maps: Drawing and analyzing attention maps to visualize which parts of the traffic sign images the models focus on during classification.
# Dataset
The German Traffic Sign Recognition Benchmark (GTSRB) dataset is used for this project. It contains over 50,000 images of traffic signs categorized into 43 classes.
# Data Preparation
The data preparation step involves:
Loading the images and labels from the dataset.
Preprocessing the images (resizing, normalization, etc.).
Splitting the dataset into training, validation, and test sets.
# Model Implementation
ResNet-18
ResNet-18 is a deep convolutional neural network with 18 layers, known for its residual learning framework that helps mitigate the vanishing gradient problem.
# Vision Transformer (ViT)
Vision Transformer is a novel architecture that applies transformers, originally designed for natural language processing, to image recognition tasks.
# Training and Evaluation
Both models are trained on the GTSRB dataset using the same training parameters for a fair comparison. The evaluation includes:
Calculating accuracy, precision, recall, and F1-score.
Comparing the performance of ResNet-18 and Vision Transformer.
# Attention Maps
Attention maps are generated to visualize which parts of the images the Vision Transformer model focuses on during the classification process. This helps in understanding the decision-making process of the model.
#Results
The performance of ResNet-18 and Vision Transformer models is compared in terms of accuracy and other evaluation metrics. Attention maps provide additional insights into the model's focus areas.
