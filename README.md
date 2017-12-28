# VQ-VAE for Audio
Implementation of VQ-VAE for audio as described the DeepMind's paper
[here](https://arxiv.org/abs/1711.00937).

There exists several implementations of VQ-VAE using PixelCNN as the
encoder/decoder.
- https://github.com/nakosung/VQ-VAE
- https://github.com/hiwonjoon/tf-vqvae

The goal in this repo is to have WaveNet as the encoder/decoder. 

### Credits
The starting code for this was adapted from 
- hiwonjoon's repo using VQ-VAE with the pixel-cnn architecture https://github.com/hiwonjoon/tf-vqvae
- ibab's repo loading audio files and the implementation of the WaveNet architecture https://github.com/ibab/tensorflow-wavenet
