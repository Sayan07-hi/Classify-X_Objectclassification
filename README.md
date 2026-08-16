# Classify-X — Image Processing & Real-Time Object Classification

A hands-on MATLAB project exploring **image processing, deep learning, and real-time object classification using a mobile camera**.

## 📌 Overview

This project was developed as part of my learning experience with MATLAB and the Classify-X workshop. It combines concepts from **Image Processing Onramp** and **Deep Learning Onramp** with a practical object-classification application.

The project uses **MATLAB Online** and **MATLAB Mobile** to capture images from a smartphone camera and classify objects using pretrained deep-learning networks.

## 🧠 What I Learned

### Image Processing

Through the MATLAB Image Processing Onramp, I learned the fundamentals of:

* Digital images and image representation
* Image visualization and manipulation
* Image preprocessing
* RGB and grayscale images
* Image segmentation and thresholding
* Understanding foreground and background
* Working with images using MATLAB

### Deep Learning

Through the MATLAB Deep Learning Onramp, I learned about:

* Fundamentals of deep learning
* Neural networks
* Convolutional Neural Networks (CNNs)
* Image classification
* Training and using deep-learning models
* Pretrained neural networks
* Using MATLAB's deep-learning tools for computer vision

## 🚀 Project: Object Classification

The project uses a smartphone camera connected to MATLAB Online through **MATLAB Mobile**.

### Workflow

```text
Smartphone Camera
       ↓
 MATLAB Mobile
       ↓
   MATLAB Online
       ↓
 Image Capture
       ↓
 Image Preprocessing
       ↓
 Pretrained Neural Network
       ↓
 Object Classification
       ↓
 Predicted Object
```

The project uses two pretrained neural networks:

* **GoogLeNet**
* **SqueezeNet**

Images captured using the mobile camera are resized and converted into the required format before being passed to the networks for classification.

## ⚡ Real-Time Object Classification

I also implemented a **real-time/continuous object-classification workflow**, where images captured using the mobile camera are processed and classified using pretrained deep-learning models.

The system demonstrates the complete pipeline from **camera input to AI-based object recognition**.

## 🛠️ Technologies Used

* MATLAB
* MATLAB Online
* MATLAB Mobile
* Image Processing
* Deep Learning
* Convolutional Neural Networks
* GoogLeNet
* SqueezeNet
* Smartphone Camera

## 📂 Project Contents

```text
Classify-X/
│
├── Classify_X.m
├── Classify_X.pdf
└── README.md
```

## 🎯 Learning Outcome

This project helped me connect theoretical concepts from **image processing and deep learning** with a practical computer-vision application.

It was also my first hands-on experience integrating a **smartphone camera with MATLAB** and using pretrained neural networks for object classification.

---

### 📚 Learning Resources

* MATLAB Image Processing Onramp
* MATLAB Deep Learning Onramp
* MathWorks Classify-X Workshop
