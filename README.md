
# PixelArtGAN

## Overview

PixelArtGAN is a project that utilizes a Deep Convolutional Generative Adversarial Network (DCGAN) to generate pixel art characters. The model is designed to create diverse pixel characters belonging to three classes: humanoid, monsters, and animals. The implementation is based on TensorFlow and Keras.
<br>

## Introduction

Generative Adversarial Networks (GANs) have shown remarkable success in generating realistic content across various domains. PixelArtGAN focuses on the creative task of generating pixel art characters, with a particular emphasis on humanoid, monsters, and animals. The project demonstrates the application of a DCGAN architecture to produce pixel characters based on a dataset of 16x16 pixel images.

## Features

- DCGAN architecture for pixel character generation.<br>
- Three classes: humanoid, monsters, and animals.<br>
- Training process with detailed model architecture and data preprocessing.<br>
- Results and evaluations of the generated pixel characters.<br>


### Prerequisites

- TensorFlow<br>
- Keras

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/PixelArtGAN.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Preprocess your pixel character dataset and place it in the `GAN dataset` directory.<br>
2. Adjust hyperparameters and configurations in the code as needed.<br>
3. Run the training cell<br>
4. Evaluate the results and visualize generated pixel characters.<br>


## Data Preprocessing

Ensure proper preprocessing of your pixel character dataset, including resizing to 16x16 pixels, normalization, and optional data augmentation. Refer to the [Data Preprocessing](#data-preprocessing) section for more details.<br>

## Contributing

Feel free to contribute by opening issues, providing suggestions, or submitting pull requests. Your input is highly appreciated!<br>

---