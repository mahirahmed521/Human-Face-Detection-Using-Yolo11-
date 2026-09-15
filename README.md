🤖 ML & Computer Vision Mini-Projects

This repository contains two distinct, lightweight Python scripts demonstrating fundamental applications in Computer Vision (Face/Person Detection) and Machine Learning (Tabular Data Classification).

📁 Project 1: Multi-Model Face & Person Detection

This script compares three different computer vision models to detect faces and people within a single image (using the classic "Lena" test image).

🔍 Models Compared:

Haar Cascade: A traditional, lightweight machine learning-based object detection method.

MTCNN (Multi-task Cascaded Convolutional Networks): A deep learning approach highly optimized for facial detection and alignment.

YOLO11 (You Only Look Once): A state-of-the-art, real-time object detection model used here for broader person detection.

📦 Dependencies for Project 1

pip install opencv-python mtcnn ultralytics matplotlib


🚀 What it Does

Downloads a test image automatically.

Processes the image through all three models.

Generates a side-by-side Matplotlib plot showing bounding boxes and detection counts for visual comparison.

📁 Project 2: Customer Purchase Classification

This script demonstrates a foundational Machine Learning workflow using tabular data. It trains a classification model to predict whether a customer will buy an item based on their Age and Income.

🧠 Core Technologies:

Algorithm: Random Forest Classifier

Library: scikit-learn

Evaluation: Accuracy Score, Classification Report, and Confusion Matrix Heatmap.

📦 Dependencies for Project 2

pip install pandas scikit-learn seaborn matplotlib


🚀 What it Does

Generates a dummy dataset of ages, incomes, and purchase history.

Splits the data into 70% training and 30% testing sets.

Trains a RandomForestClassifier.

Outputs comprehensive evaluation metrics, including a visual confusion matrix plotted with Seaborn.

⚙️ General Setup and Usage

Clone the repository to your local machine.

Install the required libraries using the commands provided above. (You can also combine them: pip install opencv-python mtcnn ultralytics matplotlib pandas scikit-learn seaborn).

Run the scripts using your terminal or favorite IDE:

python face_detection.py
python classification_model.py


(Note: Be sure to save your code snippets into separate Python files like the ones named above).
