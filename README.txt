GenAI Lab - TensorFlow notebooks (one per question)

Ques_A  (from ques_a.pdf)
  Q01 Minimax game gradients        Q08 VQ-GAN straight-through estimator
  Q02 Reparameterization trick      Q09 AE vs VAE bottleneck
  Q03 VAE loss (+ KL weight 0 demo) Q10 VAE reparameterization (Fashion-MNIST)
  Q04 GAN D / G losses              Q11 Discriminator loss + Nash equilibrium
  Q05 DCGAN dimension arithmetic    Q12 DCGAN shapes (Fashion-MNIST)
  Q06 DDPM add_noise                Q13 ViT patching (Fashion-MNIST, D=64)
  Q06b Self-attention dimensions    Q07 ViT patching (Fashion-MNIST, D=32)

Ques_B  (from ques_b.docx)
  B01 VAE MNIST (mu / log_var heads)    B09 StyleGAN2 generator (mod/demod, noise, style mixing)
  B02 GAN MNIST with BatchNorm          B14 Forward diffusion MNIST, cosine, 800 steps
  B03 Vanilla GAN (saturating, Xavier)  B19 Forward diffusion Fashion-MNIST, linear, 100 steps
  B04 Conv autoencoder                  B20 Forward diffusion EMNIST-Letters, offset cosine, 1200
  B05 VAE latent 16                     B21 LoRA
  B06 U-Net noise prediction (Pets)
  B07 ViT MNIST classifier
  B08 Text Transformer (causal mask, heatmap)
  B10-B13, B15-B18 = repeated short questions (same as the matching Ques_A notebook)

B06 and B20 need: pip install tensorflow-datasets   (Colab already has it)
