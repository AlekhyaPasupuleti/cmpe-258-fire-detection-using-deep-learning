# 🔥 Fire Detection Using Deep Learning

This project explores the use of deep learning models to detect fire in images and video frames. Developed as part of CMPE 258 coursework, it compares the performance of a custom CNN with a pre-trained ResNet50 model for binary fire classification (fire vs. no fire).

## 👨‍💻 Contributors

- Alekhya Pasupuleti - 016622372  
- Pavan Satyam - 016422172  
- Piyush Gade - 016420898  
- Shravani Naikoti - 016673579

## 🧠 Project Overview

- 📂 Dataset: Fire and Non-Fire images (custom/pre-collected)
- 🧪 Models used:
  - Custom-built Convolutional Neural Network (CNN)
  - Transfer Learning using ResNet50
- 📊 Evaluation metrics:
  - Accuracy, Precision, Recall, F1 Score
  - Training and validation loss plots

## 📁 Files

- `Fire_Detection_CNN_and_Resnet50.ipynb` — Main Jupyter notebook containing data loading, model training, evaluation, and result visualization.
- `README.md` — Project description and setup guide.

## 🛠️ Setup Instructions


1. **Clone the repository**

```bash
git clone https://github.com/your-username/cmpe-258-fire-detection.git
cd cmpe-258-fire-detection-using-deep-learning-main
make sure to install:
tensorflow, keras, matplotlib, numpy, opencv-python, scikit-learn

Run the notebook

Open the notebook using Jupyter:
jupyter notebook Fire_Detection_CNN_and_Resnet50.ipynb

📈 Results
CNN Accuracy: ~85% (subject to dataset)

ResNet50 Accuracy: ~95%+

ResNet50 outperforms basic CNN in both precision and generalization

🧪 Future Improvements
Use video frame streaming for real-time fire detection

Explore object detection-based approaches (YOLO, SSD)

Expand dataset and apply data augmentation
