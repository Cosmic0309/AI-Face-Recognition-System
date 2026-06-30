# AI Face Recognition using PCA & CNN
This project implements a complete face recognition pipeline capable of identifying multiple individuals from facial images using both classical machine learning and deep learning approaches.
The system performs image preprocessing, label encoding, dataset preparation, dimensionality reduction using Principal Component Analysis (PCA), and face classification using a Convolutional Neural Network (CNN). Performance of both approaches is evaluated and compared using accuracy and loss metrics.
The project demonstrates how deep learning significantly improves recognition performance over traditional feature extraction techniques while maintaining an end-to-end machine learning workflow.

# Features
Image dataset loading from folders
- Automatic label generation
- Image resizing and normalization
- Face preprocessing using OpenCV
- Label Encoding
- Train/Test split
- PCA dimensionality reduction
- CNN-based face classification
- Model evaluation
- Accuracy comparison between PCA and CNN
- Prediction on custom images
- Confusion Matrix

# Technologies Used
- Python
- OpenCV
- NumPy
- Pandas
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Google Colab

# ML Workflow
<img width="1067" height="853" alt="Screenshot 2026-06-30 132506" src="https://github.com/user-attachments/assets/71760d13-197b-485e-92bf-87681bbc81c1" />

# Comparision Table
<img width="656" height="330" alt="model_comparision_table" src="https://github.com/user-attachments/assets/d64b19c9-4111-4530-b5d0-521286a69620" />

# Future Improvements
- MobileNetV2 Transfer Learning
- Face Detection using Haar Cascade / MTCNN
- Real-time webcam recognition
- FaceNet embeddings
- ArcFace implementation
- Anti-spoofing
- Unknown face detection
- Flask/FastAPI deployment
- Streamlit web application
