# MNIST GAN

A PyTorch implementation of a Generative Adversarial Network (GAN) trained on the MNIST dataset.

## Overview
This project implements a GAN to generate handwritten digits similar to those in the MNIST dataset. The architecture includes:
- A Generator that creates fake images from random noise
- A Discriminator that tries to distinguish between real and fake images

## Requirements
```
torch>=2.0.0
torchvision>=0.15.0
matplotlib>=3.5.0
tqdm>=4.65.0
```

## Quick Start
1. Clone the repository:
```bash
git clone https://github.com/tveshas/mnist-gan.git
cd mnist-gan
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the training:
```bash
python my_gan.py
```

## Project Structure
- `my_gan.py`: Main implementation file containing GAN architecture and training loop
- `my_gan.ipynb`: Jupyter notebook version with visualizations and explanations

## Architecture Details
- Generator: Multi-layer perceptron with batch normalization and ReLU activation
- Discriminator: Multi-layer perceptron with LeakyReLU activation
- Input dimension: 784 (28x28 MNIST images)
- Latent dimension: 64

## License
MIT License

## Acknowledgments
This implementation is based on the original GAN paper by Goodfellow et al.
