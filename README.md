# Fake Currency Detection Using CNN

This project is a Fake Currency Detection system that uses Convolutional Neural Networks (CNN) to classify images of currency notes as real or fake. It combines custom-built CNN models and powerful pretrained models like MobileNet and ResNet50 to achieve accurate detection. The system trains on labeled image datasets, performs image augmentation for robustness, and predicts the authenticity of new currency images.

---

## 🚀 Features

- Detect fake currency notes using image classification  
- Uses CNN, MobileNet, and ResNet50 with transfer learning  
- Data augmentation for better generalization  
- Visualizes training and validation accuracy  
- Save and load trained models for inference  
- Test new currency images with saved models

---
## 💡 Usage

1. Prepare your dataset folders with images labeled as real or fake currency.  
2. Run the training script to train deep learning models.  
3. Visualize training progress and accuracy graphs.  
4. Save the trained model to reuse later.  
5. Load the saved model and predict on new currency images.  
6. Get the prediction: "Real" or "Fake".

7. Make sure your dataset folder structure looks like this:

- /Train/Real/
- /Train/Fake/
- /Test/Real/
- /Test/Fake


---

## Model Overview

- Custom-built CNN for baseline currency classification.  
- MobileNet pretrained model fine-tuned on your dataset.  
- ResNet50 pretrained model fine-tuned for improved accuracy.  
- Models are trained with Adam optimizer and categorical cross-entropy loss.

---

## Results Visualization

The training scripts plot accuracy graphs to compare the performance of different models.

---

