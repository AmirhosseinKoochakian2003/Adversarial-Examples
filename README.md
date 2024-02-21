# Adversarial Examples
This project aims to reduce the precision of MobileNetV2 by conducting adversarial attacks. I have also written some notes about the [paper](https://arxiv.org/abs/1412.6572).

MobileNetV2 is a CNN model that can classify images into 1000 object categories. As we can see, the model classifies the macaw image with 94% confidence. By applying perturbation η, we can reduce this number to only 8%. Surprisingly, human eyes cannot distinguish between these two images.

<div align="center">

| <img src="images/1.png" width="400" height="400"> | <img src="images/2.png" width="400" height="400"> |
|:--:|:--:|
| *Original image* | *Noisy image* |
</div>

# Refrences
- [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) Ian J. Goodfellow, Jonathon Shlens, Christian Szegedy.
