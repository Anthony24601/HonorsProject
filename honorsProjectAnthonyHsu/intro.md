# Cover
## Exploring Gradient Descent On Image Reconstruction with EHT data

Abstract:
The Event Horizon Telescope (EHT) has revolutionized our understanding of black holes by using technology like Very Long Baseline Interfermetry (VLBI) and General Relativistic Magnetohydrodynamics (GRMHD) simulations to create high-resolution images.
This Juypter Book delves into the process of reconstructing images while showcasing images from EHT data. We investigate some key components within this process such as interpolation, calculating loss, and different gradient calculation methods.

Interpolation schemes play a pivotal role in connecting the dots between sparse observational data and reconstructing an image. It does so by estimating unknown data that fall in between existing, known data points. By studying how the real domain relates to the Fourier domain, we can understand what factors can go into recreating a high-resolution image. One approach to image reconstruction involves creating a loss function and minimizing it. The loss function quantifies how well the image matches the observational data and how same or expected the appearance of the image looks. The latter part of a loss function is called a regularizer. The optimum (the best performing image) is accepted as the image reconstruction of the data.

Finally, this notebook focuses on studying two distinct methods for computing gradients: finite differences and "dirtying the image." By evaluating their efficiency and accuracy, we hope to provide insights into selecting suitable gradient calculation methods for image reconstruction tasks. Additionally we attempt to combine all of these topics and perform gradient descent on sample test images.

```{tableofcontents}
```
