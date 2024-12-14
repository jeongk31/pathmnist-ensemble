# PathMNIST Ensemble Model Training

This repository contains a Jupyter Notebook implementation of an ensemble learning framework using three neural network architectures (SqueezeNet, MobileNetV2, and ShuffleNetV2) for the PathMNIST dataset. The notebook trains and evaluates the ensemble model and compares it with individual models.

## Features
- Ensemble learning using multiple models.
- Training and evaluation with pretrained models.
- Option to train models from scratch.
- Comparison of ensemble and individual model performance.

## Requirements
- Python 3.7+
- Jupyter Notebook
- PyTorch
- torchvision
- tqdm
- MedMNIST

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/jeongk31/pathmnist-ensemble.git
   cd pathmnist-ensemble
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage
Open the `pathmnist_ensemble.ipynb` notebook and run all cells to train and evaluate the models. The notebook outputs training, validation, and test accuracy for the ensemble and individual models.

## Results
### Ensemble Results:
- **Pretrained Ensemble**: 90.31%
- **From Scratch Ensemble**: 82.11%
- **Weight Matrix Training**: 21.06%

### Individual Model Results:
| Model         | Baseline | Fine-tuned (Scratch) | Fine-tuned (Pretrained) |
|---------------|----------|-----------------------|--------------------------|
| **SqueezeNet** | 9.99%    | 81.31%               | 85.09%                  |
| **MobileNet**  | 10.91%   | 77.30%               | 90.31%                  |
| **ShuffleNet** | 13.04%   | 80.99%               | 87.45%                  |

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
