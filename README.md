# CIFAR-10 Image Classification

**Author:** Satya Narayan Mohanty  
**University:** KIIT Deemed to be University  
**Guide:** Mr. N Biraja Isac

## Project Overview
This repository contains code and instructions to train three models on CIFAR-10:
- Baseline CNN (from scratch)
- ResNet-18 (transfer learning)
- EfficientNet-B0 (via timm)

## Files
- `train_notebook.ipynb` - Jupyter notebook with full training/eval code.
- `requirements.txt` - Python packages required.
- `models/` - Directory where trained `.pth` model files will be saved.

## Dataset
CIFAR-10 will be downloaded automatically by torchvision datasets. Alternatively:
- CIFAR-10 official page: https://www.cs.toronto.edu/~kriz/cifar.html

## How to run
1. Create a virtual environment and install requirements:
   ```
   pip install -r requirements.txt
   ```
2. Start Jupyter and open `train_notebook.ipynb`.
3. Follow cells; optionally reduce `num_epochs` for quick tests.
4. Trained models will be saved to `models/`.

## Notes
- Training requires a GPU for reasonable time. Use Google Colab / Kaggle / your local GPU.
- For EfficientNet install `timm` (included in requirements).

