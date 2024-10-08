# Autoencoder and Variational Auto-Encoders (VAEs) for Image Processing: An Educational Tutorial
## Project Overview
This repository contains an educational tutorial on implementing auto-encoders and VAEs using PyTorch, focusing on image processing. The project uses the MNIST dataset to demonstrate the principles of autoencoders, including how they can be used for compression, noise removal, anomaly detection and data generation.

## Learning Objectives
- Understand the concept and architecture of Auto-Encoders and Variational Auto-Encoders.
- Explore image compression.
- Experiment with different compression ratios and analyze the impact on image quality.
- Explore noise removal.
- Explore anomaly detection.
- Generate new unseen data.
Installation
To get started, clone this repository and install the required packages in **`requirements.txt`**:

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```
## Tutorial Outline
The `auto_encoder.ipynb` notebook walks through the following steps:

- Data Preparation: Loading and preprocessing the MNIST dataset.
- Model Building: Defining the auto-encoder architecture.
- Model Training: Training the model to learn efficient data encoding.
- Compression and Decompression: Demonstrating how to compress and decompress images.
- Visualization: Comparing original, compressed, and decompressed images.

The `vae.ipynb` notebook walks through the following steps:
- Model Building
- Data compression
- Data generation
- Noise removal
- Anomaly detection
- Missing values imputation



## Example Outputs
The tutorial includes visual examples of original, compressed, and decompressed images at various compression ratios to illustrate the effectiveness of the trained auto-encoder.

## Project publication
Click [here](https://app.readytensor.ai/publications/image_compression_using_a_simple_autoencoder_4SAKUg8ciBuV) for the project publication.

# License
This project is provided under the MIT License. Please see the LICENSE file for more information.

# Contact
Repository created by Ready Tensor, Inc. (https://www.readytensor.ai/)
