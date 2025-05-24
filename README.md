# 🍎 Apple Disease Detection Using Deep Learning

This repository contains a Jupyter Notebook implementing an AI-based system for detecting diseases in apple leaves using image classification techniques. The model uses deep learning (CNN-based) for accurate prediction of various apple leaf diseases, contributing to smart agriculture and environmental conservation.

## 📌 Features

- Image classification for apple leaf diseases.
- Preprocessing pipeline for image augmentation and normalization.
- CNN-based deep learning model.
- Training and validation performance visualization.
- Real-time prediction on custom images.

## 📁 File Structure

```
AI-ML/
├── Apple_Disease_Detection.ipynb    # Main Jupyter Notebook
└── README.md                        # Project documentation
```

## 🧠 Model Overview

The notebook performs the following tasks:

1. **Dataset Loading**: Loads apple leaf images categorized into four classes.
2. **Preprocessing**: Resizes, augments, and normalizes images using TensorFlow/Keras preprocessing.
3. **Model Building**: Defines a Convolutional Neural Network for multi-class classification.
4. **Training**: Trains the model on the preprocessed dataset and validates its performance.
5. **Evaluation**: Outputs accuracy, loss graphs, and confusion matrix.
6. **Prediction**: Allows inference on new, unseen apple leaf images.

## 📊 Dataset

The dataset used in this project is structured with labeled folders for each class. It may have been sourced from the [PlantVillage Dataset](https://www.kaggle.com/datasets/ambityga/apple-leaf-disease-dataset), but ensure to cite the dataset if used from an external source.

### Classes:
- `Apple___Apple_scab`
- `Apple___Black_rot`
- `Apple___Cedar_apple_rust`
- `Apple___healthy`

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Apple_Disease_Detection.git
   cd Apple_Disease_Detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Apple_Disease_Detection.ipynb
   ```

4. Follow the instructions in the notebook to train and test the model.

## 🛠 Requirements

- Python 3.7+
- TensorFlow/Keras
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

You can install all dependencies using:
```bash
pip install tensorflow numpy matplotlib scikit-learn jupyter
```

## 📈 Results

The model achieves high accuracy in classifying apple diseases under standard training conditions. Graphs for accuracy/loss and confusion matrix are included in the notebook for performance interpretation.

## 🔍 Example Predictions

The notebook demonstrates predictions on sample test images and shows the class label with confidence scores.

## 🧪 Applications

- Precision agriculture
- Automated crop health monitoring
- Environmental conservation
- Smart farming tools

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## 👨‍💻 Author

- **Kashish Devgan** – [https://github.com/kashish_devgan](https://github.com/kashish-devgan)
