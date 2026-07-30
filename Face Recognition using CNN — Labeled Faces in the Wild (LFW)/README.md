# Face Recognition using Convolutional Neural Networks (CNN)

## Objective
The objective of this project is to develop a Convolutional Neural Network (CNN) model to recognize faces from the Labeled Faces in the Wild (LFW) dataset. The model aims to achieve high classification accuracy while effectively identifying different individuals from grayscale facial images.

---

## Dataset

**Labeled Faces in the Wild (LFW)**

The dataset contains:
- **1,288 grayscale face images**
- **7 public figures**
- Image size: **50 × 37 pixels**
- Images resized using a factor of **0.4**
- Images per person range from **70 to 530**

### Classes
- Ariel Sharon
- Colin Powell
- Donald Rumsfeld
- George W. Bush
- Gerhard Schroeder
- Hugo Chavez
- Tony Blair

---

## Technologies and Libraries Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn

---

## Methodology

1. Installed and imported the required libraries.
2. Loaded the LFW dataset using `fetch_lfw_people()`.
3. Performed Exploratory Data Analysis (EDA) and visualized sample images.
4. Preprocessed the images and reshaped them for CNN input.
5. Split the dataset into training and testing sets (80:20).
6. Applied data augmentation using `ImageDataGenerator`.
7. Built a CNN consisting of:
   - Three Convolutional layers
   - Batch Normalization
   - Max Pooling
   - Dropout layers
   - Dense layer
   - Softmax output layer
8. Trained the model using the Adam optimizer and Sparse Categorical Crossentropy loss.
9. Used Early Stopping and ReduceLROnPlateau callbacks to improve performance.
10. Evaluated the model using test accuracy, classification report, and confusion matrix.
11. Visualized training/validation accuracy, loss curves, and prediction results.

---

## Model Architecture

- Conv2D (32 Filters, ReLU)
- Batch Normalization
- MaxPooling2D
- Dropout (0.25)

- Conv2D (64 Filters, ReLU)
- Batch Normalization
- MaxPooling2D
- Dropout (0.25)

- Conv2D (128 Filters, ReLU)
- Batch Normalization
- MaxPooling2D
- Dropout (0.25)

- Flatten
- Dense (128 Units, ReLU)
- Dropout (0.5)
- Dense (7 Units, Softmax)

---

## Training Configuration

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Batch Size: 32
- Epochs: 80
- Data Augmentation: Rotation, Zoom, Horizontal Flip, Width & Height Shift
- Callbacks:
  - Early Stopping
  - Reduce Learning Rate on Plateau

---

## Results

- **Training Accuracy:** 86.70%
- **Validation Accuracy:** 96.51%
- **Final Test Accuracy:** **97.67%**
- **Test Loss:** **0.1064**

The CNN successfully exceeded the target accuracy of **90%**, achieving **97.67%** on the LFW test dataset. The confusion matrix and classification report showed excellent precision, recall, and F1-score across all seven classes.

---

## Visualizations

The project includes:
- Sample face images
- Training vs Validation Accuracy
- Training vs Validation Loss
- Face prediction results
- Confusion Matrix
- Classification Report

---

## Conclusion

This project demonstrates the effectiveness of Convolutional Neural Networks (CNNs) for face recognition tasks. By combining data augmentation, batch normalization, dropout regularization, and learning rate scheduling, the model achieved outstanding performance with **97.67% test accuracy**. The approach is robust and can be extended to larger face recognition datasets and real-world applications.

---

## Future Enhancements

- Train on larger face datasets
- Apply Transfer Learning (VGG16, ResNet50, EfficientNet)
- Face Detection + Face Recognition pipeline
- Real-time face recognition using OpenCV
- Deploy the model as a web application using Streamlit or Flask

---

## Author

**Anet Davis**  
**Registration Number:** 23BHI10146
