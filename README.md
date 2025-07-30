# Lab-3_Foundations-of-Machine-Learning-Frameworks

#  Cats vs Dogs Classifier

This project builds and compares two models for classifying images of cats and dogs:

1. **Custom CNN** – A basic convolutional neural network trained from scratch.
2. **VGG16 Fine-Tuned** – A transfer learning approach using the pre-trained VGG16 model.

---

##  Dataset

- Source: Kaggle (Cats vs Dogs)
- Structure: `train/`, `validation/`, `test/` folders with `cat/` and `dog/` subfolders

---

##  Features

- Image Preprocessing
- Data Augmentation (rotation, shift, flip, zoom)
- Model Training & Validation
- Performance Evaluation (Accuracy, Precision, Recall, F1-score, PR Curve)
- Confusion Matrix & Misclassified Samples

---

## Output
models/best_custom_cnn.keras

models/best_vgg16_finetuned.keras

Use Git LFS to track model files if pushing to GitHub.
