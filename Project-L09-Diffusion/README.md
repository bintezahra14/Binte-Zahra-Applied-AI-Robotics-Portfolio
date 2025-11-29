# L09 – Diffusion Model for MNIST Generation

**Course:** ITAI 2376 – Deep Learning  
**Task:** Generate MNIST-style digits with a diffusion model

This Colab notebook builds a **diffusion model** in PyTorch:

- Uses MNIST (28×28 grayscale) with normalization and DataLoaders  
- Defines a U-Net with:
  - `GELUConvBlock`, `DownBlock`, `UpBlock`, and space-to-depth downsampling
  - sinusoidal **time embeddings** for timesteps
  - **class embeddings** for digit labels  
- Trains a denoising network that turns random noise into clear digit images over many timesteps :contentReference[oaicite:6]{index=6}  

## File

- `L09_Diffusion_BinteZahra_notebook_ITAI_2376.ipynb - Colab.pdf` – notebook export

## What I Learned

- High-level intuition behind diffusion models  
- How U-Net architectures, time embeddings, and class conditioning work together  
- Practical GPU setup, seeding, and debugging for generative models
