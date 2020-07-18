# AI-for-Medical-Diagnosis

AI for Medical Diagnosis contains three assignments.

# 1) Chest X-Ray Medical Diagnosis with Deep Learning

In this assignment! We will explore medical image diagnosis by building a state-of-the-art chest X-ray classifier using Keras.

The assignment will walk through some of the steps of building and evaluating this deep learning classifier model. In particular, we will:

* Pre-process and prepare a real-world X-ray dataset
* Use transfer learning to retrain a DenseNet model for X-ray image classification
* Learn a technique to handle class imbalance
* Measure diagnostic performance by computing the AUC (Area Under the Curve) for the ROC (Receiver Operating Characteristic) curve
* Visualize model activity using GradCAMs

In completing this assignment we will learn about the following topics:

* Data preparation
* Visualizing data
* Preventing data leakage
* Model Development
* Addressing class imbalance
* Leveraging pre-trained models using transfer learning
* Evaluation
* AUC and ROC curves

# 2) Evaluation of Diagnostic Models

In this assignment, we will be working with the results of the X-ray classification model we developed in the previous assignment. In order to make the data processing a bit more manageable, we will be working with a subset of our training, and validation datasets. We will also use our manually labeled test dataset of 420 X-rays.

As a reminder, our dataset contains X-rays from 14 different conditions diagnosable from an X-ray. We’ll evaluate our performance on each of these classes using the classification metrics we learned in lecture.

# 3) Brain Tumor Auto-Segmentation for Magnetic Resonance Imaging (MRI)

We will learn how to build a neural network to automatically segment tumor regions in brain, using MRI (Magnetic Resonance Imaging) scans.

The MRI scan is one of the most common image modalities that we encounter in the radiology field. Other data modalities include:

* Computer Tomography (CT),
* Ultrasound
* X-Rays.

In this assignment we will be focusing on MRIs but many of our learnings applies to other mentioned modalities as well. We’ll walk you through some of the steps of training a deep learning model for segmentation. We will learn:

* What is in an MR image
* Standard data preparation techniques for MRI datasets
* Metrics and loss functions for segmentation
* Visualizing and evaluating segmentation models
