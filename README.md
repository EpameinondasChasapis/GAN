 Factorisation in Generative Jets

## Table of Contents

- [Project Description](#project-description)
- [Observables and Data](#observables-and-data)
- [Models](#models)
  - [GAN models](#gan-models)
- [summary](#summary)

## Project Description

## Observables and Data

In this [notebook](./ExploringPythiaData.ipynb) the data used is described and the relevant features explained.
- [ ] Features of the data E, px, py, pz
- [ ] Jet Clustering
- [ ] Indicators of Factorisation
  - [x] EEC
  - [ ] metrics for correct simulation (KL)

## Models

### GAN models

- [x] [GAN](./GANInputs.ipynb)
  - [ ] Unscaled
  - [x] Standard/MinMax Scaler
  - [ ] Relative Scalar (to the jet)
- [x] [WGAN](./OnShellGAN.ipynb) 
    - [x] Custom Training Functions
    - [ ] Weight Clipping
    - [x] On-shell conditioning
- [x] cWGAN
  - [ ] Choice of conditioning Variables
  - [ ] Latent Variables (Hybrid VAE-GAN?)
- [ ] Other models

## summary