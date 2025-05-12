# Rice Type Classification (Tabular Data)

This project uses a neural network with PyTorch to classify different types of rice grains based on tabular features from the [Kaggle dataset](https://www.kaggle.com/datasets/mssmartypants/rice-type-classification).

## Dataset
- Source: Kaggle
- Features: Area, Perimeter, Compactness, Kernel Length, Width, Asymmetry, etc.
- Target: Rice type (e.g., Arborio, Basmati, etc.)

## Model
- Framework: PyTorch
- Type: Feedforward Neural Network
- Optimizer: Adam
- Loss: CrossEntropyLoss

## Results
- Training accuracy: 98%
- Validation accuracy: 95%
- Visualizations: Loss/accuracy plots

## How to Run
1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Train the model using:
- Google Colab (`rice_classification.ipynb`) or
- Python script (optional)

## Acknowledgments
- Dataset by mssmartypants on Kaggle
