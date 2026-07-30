# CIFAR-10 Image Classification using Convolutional Neural Networks (CNN)

## Objective
The objective of this project is to classify images from the CIFAR-10 dataset using a Convolutional Neural Network (CNN). The model learns to identify images belonging to one of the ten object categories with high accuracy.

---

## Dataset
**CIFAR-10 Dataset**

The dataset consists of:
- 50,000 training images
- 10,000 testing images
- Image size: **32 × 32 × 3 (RGB)**

### Classes
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## Libraries Used

```python
import tensorflow as tf
import numpy as np
import matplotlib.pyplot as plt
from tensorflow.keras.datasets import cifar10
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Conv2D, MaxPooling2D, Flatten, Dense, Dropout
```

---

## Methodology

1. Loaded the CIFAR-10 dataset.
2. Normalized image pixel values.
3. Built a CNN model.
4. Trained the model using the training dataset.
5. Evaluated the model on the test dataset.
6. Visualized the training accuracy and loss.

---

## Model Architecture

- Conv2D (32 Filters, 3×3, ReLU)
- MaxPooling2D
- Conv2D (64 Filters, 3×3, ReLU)
- MaxPooling2D
- Conv2D (64 Filters, 3×3, ReLU)
- Flatten
- Dense (64 Units, ReLU)
- Dropout
- Dense (10 Units, Softmax)

---

## Training

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 20–50
- Batch Size: 64

---

## Results

- Achieved approximately **75–88%** test accuracy.
- Successfully classified images into ten categories.
- Training and validation accuracy improved over epochs.

---

## Conclusion

This project demonstrates the effectiveness of Convolutional Neural Networks (CNNs) for image classification. The model achieved good performance on the CIFAR-10 dataset and provides a foundation for experimenting with deeper architectures, data augmentation, and transfer learning techniques.

---

## Future Enhancements

- Data Augmentation
- Transfer Learning (ResNet, VGG16)
- Hyperparameter Tuning
- Learning Rate Scheduling

---

## Author

**Anet Davis**  
**Registration Number:** 23BHI10146
