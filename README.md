# resnet18-flower-recognition

# Flower Classification (ResNet18)

This project classifies flower images using a pre-trained ResNet18 model.

Dataset: Kaggle Flowers Recognition  
Classes: daisy, dandelion, rose, sunflower, tulip  
Number of classes: 5  

---


- ResNet18 (pre-trained on ImageNet)
- All layers frozen
- Final layer changed to 5 outputs
- Only final layer trained


## Training
Version 1:
- Optimizer: Adam
- Learning rate: 0.0001
- Batch size: 32
- Epochs: 10

Version 2:
- Optimizer: SGD
- Learning rate: 0.001
- Momentum: 0.9
- Batch size: 32
- Epochs: 10



## Seed
SEED = 20240307



## Results
- Accuracy comparison
- Training curves
- Confusion matrix (5x5)
- 10 sample predictions



## How to run
1. Upload dataset as zip in Google Colab
2. Extract to /content/flowers
3. Run the notebook



Author: Murad Həsənzadə
