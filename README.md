# Anime Face Generation Using GANs

This project focuses on the generation of high-fidelity anime faces using Generative Adversarial Networks (GANs). It is a self-initiated project completed over the span of March 2024 to April 2024.

## Overview

The goal of this project was to create a robust GAN capable of synthesizing realistic anime faces. The project involved designing and implementing detailed discriminator and generator architectures using Conv2D and ConvTranspose2D layers.

## Features

- **High-Quality Anime Faces:** The GAN model generates high-fidelity anime faces, showcasing significant improvements in image quality and diversity.
- **Robust Architecture:** Detailed discriminator and generator architectures designed using Conv2D and ConvTranspose2D layers.
- **Evaluation and Visualization:** Comprehensive evaluation and visualization of generated images, demonstrating the effectiveness of the GAN model.

## Architecture

### Discriminator

The discriminator is designed using a series of Conv2D layers, each followed by BatchNorm2D and LeakyReLU activation functions. The final layer is a Conv2D layer followed by a Sigmoid activation function.

### Generator

The generator is designed using a series of ConvTranspose2D layers, each followed by BatchNorm2D and ReLU activation functions. The final layer is a ConvTranspose2D layer followed by a Tanh activation function.

## Results

Comprehensive evaluation and visualization demonstrated significant improvements in image quality and diversity. The generated anime faces are of high fidelity, showing the robustness and effectiveness of the GAN model.

## Usage

To use this project, clone the repository and follow the instructions in the provided Jupyter notebooks. The project includes all necessary code for training the GAN model and generating anime faces.


## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

Special thanks to the developers and contributors of the libraries and datasets used in this project.
