# Rooftop Plant Health Classification

## Project title
**Deep Learning-Based Vegetable Plant Health Classification Using a Self-Collected Rooftop Garden Image Dataset**

## Goal
Build a deep-learning system that classifies visible plant/leaf health conditions from real photographs collected from a rooftop garden. Plant species are not required for the first version.

## Current dataset
- 33 original RGB photographs
- Original resolution: mostly 1536 x 2048 pixels
- Status: pilot/raw dataset; not yet labeled for model training

## Planned workflow
1. Review and label images
2. Collect more examples for each class
3. Clean and preprocess images
4. Split data into train/validation/test without leakage
5. Train a baseline CNN
6. Compare with transfer-learning models
7. Evaluate accuracy, precision, recall, F1-score and confusion matrix
8. Analyze errors and write the research paper

## Initial candidate classes
These are **provisional** and must be confirmed after image-by-image review:
- Healthy
- Yellowing / Discoloration
- Leaf Spot / Browning
- Insect / Physical Damage
- Dry / Severe Damage

We will not claim a specific plant disease unless there is sufficient evidence and an appropriate expert/source.

## Data policy
The `dataset/raw/` folder contains the original photos and should not be edited. Processed images and labels belong in separate folders.
