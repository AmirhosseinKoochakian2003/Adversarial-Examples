# Adversarial Examples
This project tries to reduce the percision of the MobileNetV2 by conducting adversarial attacks. I also wrote some notes about the [paper](https://arxiv.org/abs/1412.6572).

MobileNetV2 is a CNN model and can classify images into 1000 object categories. As we can see the model classify the macaw image with 94% confidence. By using perturbation η, we can reduce this number to only 8%. Surprisingly, humen eyes can not distinguish between these two images.

## Original image
![1](https://github.com/AmirhosseinKoochakian2003/Adversarial-Examples/blob/master/images/1.png)

## Noisy image
![2](https://github.com/AmirhosseinKoochakian2003/Adversarial-Examples/blob/master/images/2.png)

# Refrences
[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) Ian J. Goodfellow, Jonathon Shlens, Christian Szegedy.