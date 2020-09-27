---
title: OSTU
---

## It is uesd for [[Image thresholding]]
## [[Image Tresholding vs. Image Segmentation]]
## Image thresholding be future sub-divied into the local and global image tresholding algorithms. In global thresholding, a single threshold is used globally, for the whole image.

In local thresholding, some characteristics of some local image areas (e.g. the local contrast) may be used to choose a different threshold for different parts of the image.

Otsu’s method is a global image thresholding algorithm.
## Automatic global thresholding algorithms usually have following** steps.
**
Process the input image
Obtain image histogram (distribution of pixels)
Compute the threshold value T
Replace image pixels into white in those regions, where saturation is greater than T and into the black in the opposite cases.
## Application and Code : link https://www.learnopencv.com/otsu-thresholding-with-opencv/
##
