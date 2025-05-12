# 🧠 Face Mask Detection using Convolutional Neural Network (CNN)

A deep learning project that detects whether a person is wearing a face mask or not, using a Convolutional Neural Network (CNN) trained on a labeled dataset of facial images.

## 📁 Dataset
- Source: [Kaggle – Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)
- Classes: `with_mask`, `without_mask`
- Total Images: ~7,500+

## 🚀 Technologies Used
- Python
- TensorFlow & Keras
- NumPy, Pandas
- OpenCV, PIL
- Matplotlib, Seaborn

## 🛠️ Features
- Preprocessing pipeline: resizing, normalization, label creation
- Custom CNN architecture with convolutional, pooling, dense, and dropout layers
- Model evaluation through accuracy and loss visualization
- Predictive system using image input and OpenCV visualization

## 🧠 Model Architecture
- `Conv2D` + `MaxPooling2D` layers (32 & 64 filters)
- `Flatten` + `Dense(128)` + `Dropout(0.5)`
- `Dense(64)` + `Dropout(0.5)`
- Output: `Dense(2)` with `sigmoid` activation (binary classification)

## 📊 Results
- Achieved strong test accuracy with only 5 epochs
- Plotted training vs. validation accuracy and loss for performance evaluation

## 📸 Sample Prediction
```bash
Enter path of the image to be predicted: /content/sample_face.jpg
> The person in the image is wearing a mask
