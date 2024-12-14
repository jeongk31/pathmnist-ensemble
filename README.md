# PathMNIST Ensemble Model Training

This repository contains the implementation of an ensemble learning framework using three neural network architectures (SqueezeNet, MobileNetV2, and ShuffleNetV2) for the PathMNIST dataset. The code trains and evaluates the ensemble model and compares it with individual models.

## Features
- Ensemble learning using multiple models.
- Training and evaluation with pretrained models.
- Option to train models from scratch.
- Comparison of ensemble and individual model performance.

## Requirements
- Python 3.7+
- PyTorch
- torchvision
- tqdm
- MedMNIST

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the training and evaluation script:
```bash
python train.py
```

## Results
The script outputs training, validation, and test accuracy for the ensemble and individual models.

## License
This project is licensed under the MIT License.
