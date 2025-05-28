# Binary Classification of Endometriosis in Laparoscopic Images(Endometriosis-ResNet18)

This project focuses on developing a deep learning-based binary classification system to automatically detect endometriosis in laparoscopic images. Endometriosis is a gynecological condition that can be challenging to diagnose visually due to its subtle appearance and the need for expert interpretation.

Key Highlights:

Dataset:
Using the GLENDA Dataset (v1.5), which includes 350+ annotated images of visible endometriosis lesions and ~13,000 healthy images from laparoscopic procedures.
Model:
We leveraged transfer learning with a pre-trained Convolutional Neural Network (CNN), fine-tuning it for binary classification (Endometriosis present or absent).
Preprocessing & Augmentation:
Created balanced classes, split the dataset into training, validation, and test sets (70:15:15), and applied data augmentation to enhance generalization.
Training:
Used Binary Cross Entropy with Logits Loss, Adam optimizer, and early stopping to achieve stable and robust training.
Evaluation:
Evaluated performance with accuracy, precision, recall, F1-score, and confusion matrix.

Tools:
Python, PyTorch, scikit-learn, matplotlib for visualization and metrics.

Impact:
By automating lesion detection, this project demonstrates the potential for AI-assisted diagnostics in gynecology, supporting clinicians with a second-opinion tool and reducing variability in endometriosis identification.

