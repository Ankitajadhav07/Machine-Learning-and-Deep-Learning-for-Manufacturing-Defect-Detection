# Machine-Learning-and-Deep-Learning-for-Manufacturing-Defect-Detection
This repository contains the implementation of an automated defect detection system designed for the manufacturing industry. The project leverages machine learning and deep learning techniques to identify and classify defects, such as cracks, color spots, and missing components, in manufactured products.

Features
Automated Visual Inspection:
Pretrained Convolutional Neural Network (CNN) models for defect classification.
Object detection models for localizing defects in product images.
Real-Time Processing:
Lightweight architectures optimized for real-time inference using edge computing devices.
Scalability:
Transfer learning capabilities to adapt the system to various product categories with minimal retraining.
Key Components
Data Preprocessing:
Image resizing, normalization, and augmentation for robust model training.
Defect Detection Model:
Custom CNN architecture and pretrained models (e.g., ResNet, YOLO) for accurate defect identification.
Real-Time Inference:
Integration of TensorRT for fast, efficient model inference.
Visualization:
Matplotlib and OpenCV for displaying predictions and annotations on images.
Technologies Used
Frameworks: TensorFlow, Keras, OpenCV
Programming Language: Python
Deployment Tools: Flask for API deployment, Docker for containerization
Hardware Compatibility: NVIDIA Jetson Nano, Raspberry Pi
How to Use
Clone the Repository:
bash
Copy code
git clone https://github.com/ankitajadhav/defect-detection.git
cd defect-detection
Install Dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Application:
Train the model using the provided script or load pretrained weights.
Use the real-time inference script to predict defects on sample images.
Applications
Quality control in manufacturing
Real-time monitoring of production lines
Adaptable to various industries such as automotive, electronics, and textiles
Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for discussion.
