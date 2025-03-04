Handwriting Recognition Project
Overview
This project implements a handwriting recognition system using deep learning, specifically designed to recognize words from images (e.g., handwritten text datasets like IAM Words). It leverages the mltu library, TensorFlow for model training and inference, and converts the model to ONNX format for deployment. The project includes a model trained on a dataset (e.g., IAM Words), with evaluation and prediction scripts running in Google Colab using a GPU accelerator.

Purpose
The primary goal is to develop and evaluate a convolutional neural network (CNN) or similar model for handwritten text recognition, calculating metrics like Character Error Rate (CER) to assess performance. The project also explores model conversion to ONNX for cross-platform inference.

Prerequisites
Before running this project, ensure you have the following installed:

Python 3.10+
Google Colab (for running the notebook with GPU support)
Required Python packages (see Dependencies section)
Dependencies

Install the following dependencies using pip. You can run the following command in your terminal or Colab cell:

pip install mltu tensorflow tf2onnx opencv-python numpy pandas tqdm

Dataset
The project uses the IAM Words dataset (or a similar dataset) stored in the Datasets/IAM_Words/words directory.
Models and configurations are stored in the Models/03_handwriting_recognition/202412050543 directory, including model.keras, configs.yaml, and val.csv for validation data.

For more information please visit: https://github.com/pythonlessons/mltu/tree/main/Tutorials/03_handwriting_recognition