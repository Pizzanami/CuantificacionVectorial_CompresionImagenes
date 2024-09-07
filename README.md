# Vector Quantization for Grayscale Image Compression

## Description

This project implements a system for compressing grayscale images using **vector quantization**. The process involves dividing the images into blocks, encoding these blocks using a **codebook** generated through Particle Swarm Optimization (PSO), and performing **1-NN** to handle the encoding and decoding process.

The goal is to reduce the image size while maintaining the quality of the reconstruction.

**Note:** This project was the final submission for my Artificial Intelligence course.

## Features

- **Image Block Division**: The image is divided into blocks of a configurable size.
- **Compression via Codebook**: A codebook is used where each block is replaced by its closest match (using 1-NN).
- **Image Reconstruction**: The image is reconstructed from the encoded blocks.
- **Optimization with PSO**: The codebook is optimized using the Particle Swarm Optimization (PSO) algorithm.

## Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `matplotlib`
  - `opencv-python`

Install the dependencies with:

```bash
pip install numpy matplotlib opencv-python
