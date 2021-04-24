# ugin-p3

## Project 3: Cilia Segmentation 



Cilia are microscopic hairlike structures that extends from the surface of every cell.
The goal of this project is to predict Cilia by using the frames of grayscale video of Cilia.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Dataset:
 
The data can be found on GCP:  gs://uga-dsp/project3

The data is structured into 2 subfolders: data and masks

* data contains a bunch of folders (325 of them), named as hashes, each of which contains 100 consecutive frames of a grayscale video of cilia.

* masks contains a number of PNG images (211 of them), named as hashes (corresponding to the subfolders of data), that identify regions of the corresponding
videos where cilia is.


## UNET

In this project we have used  a library called Segmentation Models, which is a python library for Image Segmentation. This library supports 4 models: Unet, FPN, Linknet, PSPNet.
We have used Unet for this project. UNet is a convolutional neural network architecture, which is mostly used for Bio Medical Image Segmentation.

## Authors

(Ordered Alphabetically)
* Divya
* Md. Redwan Islam
* Meekail Zain

## References

* [Segmentaiton Models](https://github.com/qubvel/segmentation_models)
* [U-Net Implementation with Segmentation Models](https://www.youtube.com/watch?v=J_XSd_u_Yew)
* [U-Net](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/)

