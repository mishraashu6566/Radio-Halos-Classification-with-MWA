# Radio-Halos-Classification-with-MWA

## Overview

This repository contains code and resources for classifying radio halos using data from the Murchison Widefield Array (MWA). The project utilizes a Conditional Wasserstein GAN (cWGAN) and Denoising Diffusion Probabilistic Models (DDPMs) for generating synthetic data to enhance the radio halo classifier.
## Project Structure

- **`DDPM/`**: Contains files related to the Denoising Diffusion Probabilistic Models (DDPM) used in this project. The DDPM weights can be found in the [Releases](https://github.com/mishraashu6566/Radio-Halos-Classification-with-MWA/releases) section of this repository.
- **`Data_for_Gen_Model_Evaluation/`**: Includes datasets used for evaluating the generative model.
- **`Data_for_Gen_Model_Evaluation/`**: Includes datasets used for evaluating the generative model.
- **`Halo-data/`**: Contains the raw data related to radio halos.
- **`cWGAN/`**: Includes the code and resources for the Conditional Wasserstein GAN (cWGAN) implementation.
- **`Halo_data/`**: Directory for additional halo data.
- **`LICENSE`**: License file for the project.
- **`cwgann3-gen.model`**: Pre-trained model file for generating synthetic data.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
- Requests

You can install the necessary Python libraries using `pip`:

```bash
pip install tensorflow numpy matplotlib requests
