# Cover
## Exploring Gradient Descent On Image Reconstruction with EHT data

Abstract:
The Event Horizon Telescope (EHT) has revolutionized our understanding of black holes by using technology like Very Long Baseline Interfermetry (VLBI) and General Relativistic Magnetohydrodynamics (GRMHD) simulations to create high-resolution images.
This Juypter Book delves into the process of reconstructing images while showcasing images from EHT data. We investigate some key components within this process such as interpolation, calculating loss, and different gradient calculation methods.

Interpolation schemes play a pivotal role in connecting the dots between sparse observational data and reconstructing an image. It does so by estimating unknown data that fall in between existing, know data points. By studying how the real domain relates to the fourier domain, we can understand what factors can go into recreating a high-resolution image. Loss functions are a important part of the optimization process. This is because they quantify the difference between a reconstructed image and the real image. In order to do so we must understand how the data's peculiarities affects the loss function and it's regularization.

Finally, this notebook focuses on studying two distinct methods for computing gradients: finite differences and "dirtying the image." By evaluating their efficiency and accuracy, we hope to provide insights into selecting suitable gradient calculation methods for image reconstruction tasks. Additionally we attempt to combine all of these topics and perform gradient descent on sample test images.

```{tableofcontents}
```
