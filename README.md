# Image-Synthesis-With-Generative-Adversarial-Networks-Using-CIFAR-10

CS-GY 6953 / ECE-GY 7123 Deep Learning || Project || Spring 2024 <br />
New York University (NYU) Tandon School of Engineering <br /> <br />

WORK IN PROGRESS [WIP] <br /> <br />

## Overview



## Model Architecture




## Performance Evaluation



## Results

Generative Adversarial Network (GAN) model have performed well. The negative values of the discriminator loss indicate that the discriminator is able to distinguish between real and fake images effectively. The generator loss values indicate the ability of the generator to produce images that are realistic enough to deceive the discriminator. Loss values stabilize towards the later epochs, indicating that the model has reached a stable state. <br />

### Fréchet Inception Distance
FID score: **5.338638466847664e-13** <br /> <br />
Extremely low distance between the feature distributions of real and generated images, suggests that the generated images closely resemble the real images in terms of their visual features. <br />

### Inception Score
IS score: **2591.965195684151** <br /> <br />
Generated images are of high quality and exhibit a high degree of diversity in terms of their content and appearance. <br />

### Conclusion

Based on these evaluation metrics and inspection of generated images, GAN model has performed well, generating high-quality and diverse images that closely resemble the real ones from CIFAR-10 dataset.

## References

1. Krizhevsky, A. (2009). Learning multiple layers of features from tiny images. [click here](https://www.cs.toronto.edu/~kriz/cifar.html)

## Team Members
1. Durga Avinash Kodavalla | dk4852 <br />
2. Priyangshu Pal | pp2833 <br />
3. Ark Pandey | ap8652 <br />
