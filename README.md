# Surface Defect Detection using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify surface conditions into four categories:
- Dent
- Scratch
- Stain
- Normal

The model was built using TensorFlow/Keras and trained on image data.

---

## Dataset Details
The dataset contains four balanced classes with 120 images in each category:
- Dent
- Scratch
- Stain
- Normal

Images were resized to 128x128 pixels and normalized before training.

---

## CNN Model Explanation
The CNN model includes:
- Convolution layers
- ReLU activation
- MaxPooling layers
- Flatten layer
- Dense layers
- Output layer using Softmax activation

The model learns image features and classifies defects automatically.

---

## Business Use Case
This project can be used in the manufacturing industry for automatic quality inspection. The model can detect defects such as dents, scratches, and stains in products, helping companies improve quality control and reduce manual inspection effort.

---

## Conclusion
The CNN model successfully classified surface defects from images. The project demonstrated the use of deep learning and computer vision for image classification tasks and achieved good prediction performance on validation data.

