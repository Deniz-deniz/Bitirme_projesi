# Ship Detection Project
The aim is this project bulding a model with using google colab and detects container ship,bulk carrier,tugboat,ro-ro,tanker ships.
## Tools: 
Roboflow,Kaggle for dataset.
Yolo8.
There will be two data set one is small other one is large.
## Repository Structure / Files
bitirme_projesi.ipynb: The main source code of the project. 
demo_output/: This directory contains the finalized outputs of the training process and include this files best.pt,data.yml,results.png
best.pt: The trained model weights with the highest mean Average Precision (mAP). This file is used for testing.
data.yml: The configuration file that defines class names and dataset paths for the YOLO architecture.
results.png: Visual representation of training metrics, including Loss functions and Accuracy (mAP) scores over epochs.
Note: This is just demo and in this demo there is not all ship types included we mentioned above.
