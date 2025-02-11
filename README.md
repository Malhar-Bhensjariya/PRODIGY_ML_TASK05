# Food Recognition and Calorie Estimation Model

## Overview
This project aims to develop a model that can accurately recognize food items from images and estimate their calorie content. The model enables users to track their dietary intake and make informed food choices.

## Dataset
We utilized the **Food-101** dataset from Kaggle, which contains 101 different food categories with 101,000 images.

Dataset Link: [Food-101 Dataset](https://www.kaggle.com/dansbecker/food-101)

## Model Architecture
We implemented a deep learning model using **ResNet125** for food classification.

- **Model:** ResNet125
- **Training Accuracy:** ~94%
- **Test Accuracy:** ~91%
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Batch Size:** 32
- **Epochs:** 50

## Dependencies
To run this project, install the following dependencies:

```bash
pip install tensorflow keras numpy matplotlib pandas opencv-python
```

## Training the Model
To train the model, run the following command:

```bash
python train.py
```

## Testing the Model
To test the model on a new image:

```bash
python predict.py --image <image_path>
```

## Results
The model achieves a high accuracy of **91%** on the test set, demonstrating strong performance in recognizing food items.
