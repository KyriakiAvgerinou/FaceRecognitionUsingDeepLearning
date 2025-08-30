# Face Recognition using Deep Learning:
## Implementing a CNN from Scratch vs. Transfer Learning

## Project Overview
This project explores the problem of Face Recognition using Deep Learning.
The objective is to build a model that can identify individuals from a predefined group of people through facial images.
We approach the problem as a multi-class image classification problem.
Two different approaches are implemented and compared here: a custom Convolutional Neural Network (CNN) built from scratch, and a transfer learning solution with MobileNetV2 and fine-tuning. We use MTCNN for face detection. Data normalization and augmentation are applied to improve generalization.
While the CNN struggles to generalize and shows signs of overfitting, the MobileNetV2 model outperforms, reaching a validation accuracy of 81%, showing strong generalization, reliability and robustness.

Originally, this was one single, long Colab notebook file.
Because it could not be rendered on GitHub, it was split into the following 6 focused sub-notebooks:

- Part I — Collect Input Data,

- Part II — Inspect, Clean, and Preprocess Input Data,

- Part III — Prepare Input Data for the Model,

- Part IV-A — Build CNN from Scratch,

- Part IV-B — Use Transfer Learning,

- Part V — Resources.

## Input Data
For this project we used Kaggle's Face Recognition Dataset (https://www.kaggle.com/datasets/vasukipatel/face-recognition-dataset/data).

## Hardware
This project run on Google Colab, on NVIDIA A100 / L4 / T4 GPUs (whichever was available at run time).

## Video Presentation
There is also a video presentation available for this project at https://www.youtube.com/watch?v=J1dr6znTWms.
