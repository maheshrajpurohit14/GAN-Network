# GAN-NETWORK

📁 Project Title: Generative Models in Deep Learning
🧠 Abstract

This project explores powerful generative models—GANs (Generative Adversarial Networks) and VAEs (Variational Autoencoders)—to synthesize and reconstruct realistic image data. The models are trained on image datasets like MNIST to understand how deep neural networks can learn data distributions and generate new instances with similar characteristics. These models have applications in content creation, data augmentation, and anomaly detection.
📜 Project Files

File Name Description GAN.ipynb:- Implementation of a basic GAN architecture

Variational AE.ipynb:- Variational Autoencoder for image reconstruction

generative_models.ipynb:- Consolidated models and results
⚙️ Program Overview
1. GAN.ipynb

Defines Generator and Discriminator using PyTorch

Trains the GAN to generate digit images

Visualizes training loss and generated samples
2. Variational AE.ipynb

Implements Encoder and Decoder for the VAE

Uses reparameterization trick

Reconstructs and samples digits from latent space
3. generative_models.ipynb

Summary notebook containing both GAN and VAE comparisons

Shows results side-by-side with clear loss plots and outputs
🚀 How to Run

Clone the repository

git clone https://github.com/NAGINENIROHITH/GAN-NETWORK.git
cd GAN-NETWORK

Open the notebooks in Google Colab or any Jupyter environment.

Run each notebook sequentially and observe the generated outputs.
📊 Dependencies

Python 3.10+

PyTorch

matplotlib

torchvision

numpy

IPython
✅ Results

GAN successfully generates synthetic digit-like images.

VAE can reconstruct input images and perform smooth latent sampling
