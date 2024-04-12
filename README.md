<img width="235" alt="image" src="https://github.com/vaishali18lalit/UCC_AI_QUEST_2024/assets/148451703/e773ccdf-b4c6-4d91-996f-0fd2445b6dea"># UCC_AI_QUEST_2024
# Drone Image Segmentation for Irish Natural Places
## Overview
This project focuses on performing image segmentation on images captured by drones over various natural landscapes in Ireland. Image segmentation is a computer vision technique used to partition an image into multiple segments or regions based on certain characteristics, such as colors, textures, or edges. In this project, we aim to segment images to identify different objects or features in the landscape, such as vegetation, water bodies, buildings, and roads.

## Motivation
Drones provide a unique perspective for capturing high-resolution images of natural landscapes, which can be valuable for environmental monitoring, land management, and conservation efforts. By performing image segmentation on these images, we can gain insights into the composition and distribution of different elements within the landscape. This information can be used for various applications, including habitat mapping, ecological studies, and resource management.

## Approach
Our approach to image segmentation involves utilizing state-of-the-art deep learning models. In particular, we leverage Segformer, a recent advancement in segmentation models. Segformer is a transformer-based architecture specifically designed for image segmentation tasks. It combines the scalability and flexibility of transformers with the spatial information preservation of convolutional neural networks. By utilizing Segformer, we aim to achieve accurate and efficient segmentation of drone images of Irish natural places.

## Dataset
The dataset used in this project consists of images captured by drones over various natural places in Ireland. These images are manually annotated to provide ground truth labels for training the segmentation models. The dataset includes images of forests, lakes, mountains, coastlines, and other natural features commonly found in Irish landscapes.]

## Usage
Preprocess the dataset: Perform any necessary preprocessing steps, such as resizing, normalization, or augmentation, on the dataset images.

Train the Segformer model: Train the Segformer model on the annotated dataset to learn to segment different objects or features in the images.

Evaluate the model: Evaluate the trained model on a separate validation or test set to assess its performance in segmenting unseen images.

Perform inference: Use the trained model to perform segmentation on new drone images to identify and visualize different elements within the landscape.
# RESULTS:-

## Mean IOU (Intersection over Union) Scores:
Validation Set: 0.881
Testing Set: 0.8286



Fig 4.1: Performance vs. Model Efficiency

