# Face_Recognition

Overview:

This project implements a Face Recognition System using Keras FaceNet, MTCNN (Multi-task Cascaded Convolutional Networks) for face detection, and OpenCV for image processing. The model extracts embeddings from face images and uses cosine similarity for identification.

A)Features:

1.Face detection using MTCNN.

2.Embedding extraction using FaceNet.

3.Cosine similarity for face recognition.

4.Dataset preparation for training & testing.

5.No real-time recognition required (works on static images).

B)Technologies Used:

1.Python

2.OpenCV (for image processing)

3.MTCNN (for face detection)

4.Keras FaceNet (for face embedding extraction)

5.Scikit-learn (for cosine similarity calculation)

C)Project Workflow:

1. Face Detection

i)Load images using OpenCV.
ii)Detect faces using MTCNN.
iii)Extract bounding boxes (x, y, width, height).
iv)Crop and preprocess face images.

2. Feature Extraction & Encoding

i)Convert face images to 160x160 pixels.
ii)Use FaceNet to generate 128-dimensional embeddings.
iii)Normalize embeddings.

3. Face Recognition (Identification)

i)Store embeddings of known individuals.
ii)Compute cosine similarity between test and stored embeddings.
iii)Identify the most similar face from the dataset.


D)References:

Dataset Link: https://www.kaggle.com/datasets/vasukipatel/face-recognition-dataset
