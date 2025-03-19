# Face_Recognition

Overview:

This project implements a Face Recognition System using Keras FaceNet, MTCNN (Multi-task Cascaded Convolutional Networks) for face detection, and OpenCV for image processing. The model extracts embeddings from face images and uses cosine similarity for identification.

Features:

Face detection using MTCNN.

Embedding extraction using FaceNet.

Cosine similarity for face recognition.

Dataset preparation for training & testing.

No real-time recognition required (works on static images).

Technologies Used

Python

OpenCV (for image processing)

MTCNN (for face detection)

Keras FaceNet (for face embedding extraction)

Scikit-learn (for cosine similarity calculation)

Project Workflow:

1. Face Detection

Load images using OpenCV.
Detect faces using MTCNN.
Extract bounding boxes (x, y, width, height).
Crop and preprocess face images.

2. Feature Extraction & Encoding

Convert face images to 160x160 pixels.
Use FaceNet to generate 128-dimensional embeddings.
Normalize embeddings.

3. Face Recognition (Identification)

Store embeddings of known individuals.
Compute cosine similarity between test and stored embeddings.
Identify the most similar face from the dataset.


References:

Dataset Link: https://www.kaggle.com/datasets/vasukipatel/face-recognition-dataset
