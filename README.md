# MR-Image-Preprocessing-Framework
This is a design of a preprocessing framework for cleaning MR images. The framework will include the following filters: denoising, inhomogeneity (bias) correction and intensity standardization in this order. Preprocessing filters types are Correcter, Anisotropic and HistogramMatching. You are free to use available ITK filters for this purpose. Make sure that your denoising filter will preserve edges while removing noise.

## Preprocessing Proton Density (PD) Images
• Download BrainWeb images of PD data set (1mm, 0% of noise, and intensity uniformity of 0%) from http://brainweb.bic.mni.mcgill.ca/brainweb/selection_normal.html. Call them clean images.
• Download BrainWeb images of PD data set (1mm, 9% of noise, and intensity uniformity of 40%) from http://brainweb.bic.mni.mcgill.ca/brainweb/selection_normal.html. Call them unclean images.
• Process unclean images with denoising, intensity standardization, and inhomogeneity correction filters in correct consecutive order.
• Compare processed image with respect to the clean image by differing them, and reporting the mean and standard deviation of the differed image 
