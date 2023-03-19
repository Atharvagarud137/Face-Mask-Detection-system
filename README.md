# Face-Mask-Detection-system
This project uses the MTCNN (Multi-Task Cascaded Convolutional Neural Network) algorithm to detect whether people in images are wearing face masks or not. The goal is to provide a tool to help enforce safety regulations during the COVID-19 pandemic.

## Algorithm

The MTCNN algorithm detects faces in images and applies three deep neural networks to perform facial landmark detection, face alignment, and face classification. The classification network is trained on images of people wearing and not wearing face masks, allowing it to accurately classify faces in real-world images.

## Dataset

The dataset used to train the classification network consists of 1,915 images of people wearing face masks and 1,918 images of people not wearing face masks. The images were collected from various online sources and manually labeled by human annotators.
