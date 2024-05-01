# Cover
## Exploring Gradient Descent On Image Reconstruction with EHT data

Abstract:
The Event Horizon Telescope (EHT) has revolutionized our understanding of black holes by using Very Long Baseline Interferometry (VLBI) to reconstruct the highest resolution images of black holes. It combines data from a global network of radio telescopes to observe the immediate surroundings of black holes, particularly focusing on the supermassive black hole in the galaxy M87 and the center of our Milky Way. This Jupyter Book explores the intricate process of image reconstruction from EHT data, highlighting several critical aspects such as interpolation, loss calculation, and gradient computation methods.

Interpolation schemes play a pivotal role in connecting the snap averaged data in EHT's sparse observation and reconstructing an image. By examining the relationship between the image and Fourier domains, we gain insights into the factors influencing high-resolution image recreation. One approach to image reconstruction involves creating a loss function and minimizing it. The loss function quantifies how well the image matches the observational data and how same or expected the appearance of the image looks. The latter part of a loss function is called a regularizer. The optimum (the best performing image) is accepted as the image reconstruction of the data.

Additionally, this notebook assesses two distinct methods for computing gradients: finite differences and an "dirtying the image" approach. By comparing their efficiency and accuracy, we aim to offer guidance on selecting appropriate gradient computation methods for image reconstruction tasks. Integrating these components, we perform gradient descent on sample test images to demonstrate practical applications of these theories.

```{tableofcontents}
```
