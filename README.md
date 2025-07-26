# README for Image_Generator Repository

## Overview

This repository provides a Jupyter Notebook for exploring and generating images with Generative Adversarial Networks (GANs), specifically focusing on the latent space of a GAN generator. The notebook allows you to visualize how changing the latent vector's values influences the generated images, offering an intuitive way to understand the structure and capabilities of GANs.

## Features

- **Latent Space Interpolation**: Explore how linear transitions in the latent space produce smooth visual changes in generated images.
- **Image Generation**: Generate synthetic images by sampling points from the GAN’s latent space.
- **Visualization**: Plot and compare images generated from different latent space directions.

## Getting Started

### Prerequisites

- Python 3.6+
- Jupyter Notebook
- Common deep learning libraries (such as TensorFlow or PyTorch, depending on the notebook's code)
- Other dependencies as specified in the notebook (`requirements.txt` if available)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/idj997/Image_Generator.git
   ```
2. Navigate to the folder:
   ```
   cd Image_Generator
   ```
3. Install dependencies (adapt to actual requirements in the notebook):
   ```
   pip install -r requirements.txt
   ```

### Usage

1. Open the notebook in Jupyter:
   ```
   jupyter notebook 02-GAN-generator-latent-space.ipynb
   ```
2. Follow the step-by-step cells to:
   - Sample latent vectors
   - Generate images
   - Visualize how latent vector interpolation changes image synthesis

## Project Structure

```
Image_Generator/
│
├── 02-GAN-generator-latent-space.ipynb   # Main notebook for latent space exploration
├── requirements.txt                      # List of dependencies (if provided)
└── README.md                             # This file
```

## Example Applications

- Understanding how GANs map latent space to images
- Demonstrating the interpretability of deep learning generative models
- Rapidly generating variations of images for data augmentation or creative synthesis

## License

See the repository’s LICENSE file for details on usage and distribution.

## Acknowledgments

Inspired by foundational GAN literature and various open-source latent space exploration projects in the deep learning community[1][2][3].

[1] https://github.com/SummitKwan/transparent_latent_gan
[2] https://github.com/anvoynov/GANLatentDiscovery
[3] https://github.com/genforce/interfacegan
[4] https://github.com/idj997/Image_Generator/blob/main/02-GAN-generator-latent-space.ipynb
[5] https://github.com/abdulium/gan-inversion-stylegan2/blob/main/Task2_GANInversion_YOURNAMEHERE.ipynb
[6] https://github.com/stefan-jansen/machine-learning-for-trading/blob/main/21_gans_for_synthetic_time_series/02_TimeGAN_TF2.ipynb
[7] https://colab.research.google.com/github/AmarSaini/Epoching-Blog/blob/master/_notebooks/2020-08-10-Latent-Space-Exploration-with-StyleGAN2.ipynb
[8] https://www.machinelearningmastery.com/how-to-develop-a-conditional-generative-adversarial-network-from-scratch/
[9] https://cocalc.com/github/fchollet/deep-learning-with-python-notebooks/blob/master/first_edition/8.5-introduction-to-gans.ipynb
[10] https://arxiv.org/pdf/2102.12139.pdf
[11] https://developers.google.com/machine-learning/gan/gan_structure
[12] https://www.youtube.com/watch?v=iuQ_f3W5Ttk
[13] https://colab.research.google.com/github/harskish/ganspace/blob/master/notebooks/Ganspace_colab.ipynb
[14] https://eprints.bbk.ac.uk/id/eprint/50420/1/PhD_thesis_Pedro%20(4).pdf
[15] https://github.com/eriklindernoren/PyTorch-GAN
[16] https://github.com/lukemelas/pytorch-pretrained-gans/blob/main/README.md
[17] https://github.com/spiorf/stylegan-encoder
[18] https://github.com/nightrome/really-awesome-gan/blob/master/README.md
[19] https://github.com/omerbsezer/Generative_Models_Tutorial_with_Demo/blob/master/README.md
[20] https://kyuanlab.org/projects/Pathology-GAN/
[21] https://huggingface.co/spaces/akhaliq/JoJoGAN/blob/25378c9b4629a937a3740a94775c6b7202944a67/e4e/README.md
