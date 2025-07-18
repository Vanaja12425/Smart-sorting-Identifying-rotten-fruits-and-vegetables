﻿# Fruit & Vegetable Disease Detection (Healthy vs Rotten)

This project uses deep learning to classify images of fruits and vegetables as healthy or rotten. It leverages convolutional neural networks (CNNs) and transfer learning with pre-trained models such as EfficientNetV2M and MobileNet.

## Dataset

The dataset is sourced from Kaggle: [Fruit and Vegetable Disease (Healthy vs Rotten)](https://www.kaggle.com/datasets/muhammad0subhan/fruit-and-vegetable-disease-healthy-vs-rotten).  
It contains images in the following categories:
- Apple Healthy
- Apple Rotten
- Banana Healthy
- Banana Rotten
- Bellpepper Healthy
- Bellpepper Rotten

## Project Structure

- `fruit_and_vegetable_disease_(healthy_vs_rotten).py`  
  Main Python script for data loading, preprocessing, model training, and evaluation.
- `Note_Fruit_and_Vegetable_Disease_(Healthy_vs_Rotten).ipynb`  
  Jupyter notebook version of the workflow.
- `README.md`  
  Project documentation.

## Usage

1. **Install dependencies**  
   Make sure you have Python 3.x and the following libraries:
   - numpy
   - opencv-python
   - matplotlib
   - seaborn
   - scikit-learn
   - tensorflow
   - keras
   - kagglehub

   You can install them using pip:
   ```sh
   pip install numpy opencv-python matplotlib seaborn scikit-learn tensorflow keras kagglehub
   ```
   2. **Download the dataset**

   The scripts use `kagglehub` to download the dataset automatically. Ensure you have access to Kaggle datasets.

3. **Run the script or notebook**

   - To run the Python script:
     ```sh
     python fruit_and_vegetable_disease_(healthy_vs_rotten).py
     ```
   - Or open the notebook in Jupyter and run the cells.

## Models

- Custom CNN built from scratch
- Transfer learning with EfficientNetV2M
- Transfer learning with MobileNet

## License

This project is for educational and research purposes. Please check the dataset's license for usage restrictions.
