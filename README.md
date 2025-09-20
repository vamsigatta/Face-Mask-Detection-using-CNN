Face Mask Detection using CNN

The Face-Mask-Detection system is a deep learning project built using Convolutional Neural Networks (CNNs) to automatically identify whether a person is wearing a face mask or not. This system processes input images (from a camera feed or dataset), extracts features using CNN layers, and classifies them into two categories: “Mask” and “No Mask.”

Key Features:

Uses CNN for image classification, achieving high accuracy in detecting masked/unmasked faces.

Trained on datasets of face images with and without masks.

Preprocessing steps include image resizing, normalization, and augmentation (rotation, flipping, zooming) to improve robustness.

Can be integrated with OpenCV for real-time detection through a webcam or CCTV feed.

Lightweight enough to be deployed on edge devices like Raspberry Pi for smart surveillance.

Workflow:

Data Collection & Preprocessing – Gather images of masked/unmasked faces, apply resizing, grayscale/RGB normalization, and data augmentation.

Model Architecture (CNN) – Multiple convolutional layers with ReLU activation, pooling layers for feature extraction, and dense layers for classification.

Training – Model trained on labeled datasets with categorical cross-entropy loss and Adam optimizer.

Evaluation – Tested on unseen images to measure accuracy, precision, recall, and F1-score.

Deployment – Integrated with OpenCV/Flask/Django for real-time monitoring.

Applications:

Public surveillance in airports, malls, and offices.

Automated monitoring in workplaces, schools, and hospitals.

Edge AI deployment on IoT devices for contactless monitoring.
