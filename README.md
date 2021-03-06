# MR-Image-Preprocessing-Framework
This is a design of a preprocessing framework for cleaning MR images. The framework will include the following filters: denoising, inhomogeneity (bias) correction and intensity standardization in this order. Preprocessing filters types are Correcter, Anisotropic and HistogramMatching. You are free to use available ITK filters for this purpose. Make sure that your denoising filter will preserve edges while removing noise.

## Preprocessing Proton Density (PD) Images
• Download BrainWeb images of PD data set (1mm, 0% of noise, and intensity uniformity of 0%) from http://brainweb.bic.mni.mcgill.ca/brainweb/selection_normal.html. Call them clean images.



• Download BrainWeb images of PD data set (1mm, 9% of noise, and intensity uniformity of 40%) from http://brainweb.bic.mni.mcgill.ca/brainweb/selection_normal.html. Call them unclean images.



• Process unclean images with denoising, intensity standardization, and inhomogeneity correction filters in correct consecutive order.



• Compare processed image with respect to the clean image by differing them, and reporting the mean and standard deviation of the differed image 


# Results
<img width="526" alt="results" src="https://cloud.githubusercontent.com/assets/19553239/22058394/bcce0a6e-dd36-11e6-9963-6db623fe910b.png">


# Useful Links
Some example ITK codes can be found in the following:
http://www.itk.org/ItkSoftwareGuide
http://itk.org/Wiki/ITK/Examples
Example code for difference operation on two images: http://itk.org/Wiki/ITK/Examples/ImageProcessing/SquaredDifferenceImageFilter
 

