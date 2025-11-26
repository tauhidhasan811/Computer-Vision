# Computer Vision Algorithms

This repository showcases various computer vision algorithms implemented using Python. It includes deep learning models for image recognition, object detection, and segmentation. The project utilizes popular libraries such as TensorFlow and Keras for model development and training. Examples provided cover architectures like AlexNet, RegNet50, and MobileNetV2, demonstrating practical applications in face recognition and image segmentation.

# Run Instructions

1.  **Clone the repository:**
    *   `git clone <repository_url>`
2.  **Navigate to the project directory:**
    *   `cd <project_directory>`
3.  **Install dependencies:**
    *   `pip install -r requirements.txt` (Assuming a `requirements.txt` file exists)
4.  **Run specific notebooks:**
    *   For Face Recognition (AlexNet):
        *   `jupyter notebook Face Recognition/alex-net.ipynb`
    *   For Face Recognition (RegNet50):
        *   `jupyter notebook Face Recognition/regnet50.ipynb`
    *   For Segmentation:
        *   `jupyter notebook Segmentation/sagmentation.ipynb`
    *   For Transfer Learning (MobileNet):
        *   `jupyter notebook Transfer Learning/transferlearning-using-mobilenet.ipynb`

# Folder Structure

```
root
| ---> Face Recognition
|      | ---> alex-net.ipynb
|      | ---> regnet50.ipynb
| ---> Segmentation
|      | ---> sagmentation.ipynb
|      | ---> segmentation.md
| ---> Transfer Learning
|      | ---> Transfer Learning.md
|      | ---> transferlearning-using-mobilenet.ipynb
| ---> LICENSE
| ---> README.md
```

# File Descriptions

*   **LICENSE**: Contains the full text of the Apache License, Version 2.0, outlining terms for software use, reproduction, and distribution.
*   **README.md**: Provides a general overview of the repository's computer vision algorithms, potential libraries used, and key functionalities.
*   **Face Recognition/alex-net.ipynb**: Implements the AlexNet architecture for face recognition, defining model layers for image classification.
*   **Face Recognition/regnet50.ipynb**: Implements a face recognition system using the RegNet50 model, focusing on generating and comparing face embeddings.
*   **Segmentation/sagmentation.ipynb**: Focuses on image segmentation using deep learning with TensorFlow, setting up a CNN for pixel-level classification.
*   **Segmentation/segmentation.md**: (Description not available due to local file access limitations).
*   **Transfer Learning/Transfer Learning.md**: Outlines a transfer learning approach for image classification, detailing leveraging pre-trained models and fine-tuning.
*   **Transfer Learning/transferlearning-using-mobilenet.ipynb**: Demonstrates transfer learning using the MobileNetV2 model for image classification on a custom dataset.
