# Fashion MNIST GAN

This repository contains a Generative Adversarial Network (GAN) project trained on the **Fashion MNIST dataset**. The GAN generates realistic fashion images (e.g., clothing, shoes) by learning the underlying distribution of the dataset. The training was stopped early, but you can increase the number of epochs to achieve better results.

## Features

- **GAN Implementation**: Built using TensorFlow/Keras or PyTorch.
- **Fashion MNIST Dataset**: Generates images of fashion items like shirts, shoes, and dresses.
- **Early Stopping**: Training was stopped early, but you can modify the code to train for more epochs.
- **Easy to Use**: Includes scripts for training and generating images.

## Usage

1. Clone the repository:
  
2. Install dependencies:
   

3. Train the GAN:
  
   - **Note**: Training was stopped early. You can increase the number of epochs in the `train.py` script for better results.

4. Generate images:
   

## Requirements

- Python 3.x
- TensorFlow 2.x (or PyTorch)
- NumPy
- Matplotlib

Example `requirements.txt`:
```plaintext
tensorflow>=2.0.0
numpy>=1.19.0
matplotlib>=3.3.0
```

## Model Details

- **Generator**: Generates fake fashion images from random noise.
- **Discriminator**: Distinguishes between real and fake images.
- **Early Stopping**: Training was stopped early to save time, but you can increase the epochs for better performance.

## Example

1. Train the GAN:
  
2. Generate images:
   

Output:
- Saved generated images in the `output/` folder.

