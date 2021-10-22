# U-net-Segmentation for medical data

Inspired by 

https://towardsdatascience.com/creating-and-training-a-u-net-model-with-pytorch-for-2d-3d-semantic-segmentation-model-building-6ab09d6a0862


https://www.youtube.com/watch?v=81AvQQnpG4Q   or https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/



here there are different types of U-net for segmentation https://github.com/bigmb/Unet-Segmentation-Pytorch-Nest-of-Unets

If you data labeling is tedious for you, use https://github.com/hanyoseob/pytorch-UNET  

use other networks as encoder and decoder of U-net https://github.com/hayashimasa/UNet-PyTorch and  https://github.com/hanyoseob/pytorch-UNET

another example of cell image segmentation is https://github.com/ugent-korea/pytorch-unet-segmentation


Medical image segmentaton library https://github.com/ELEKTRONN/elektronn3


Unet semantic segmenattion on car https://github.com/milesial/Pytorch-UNet


retina vessel segmentation https://github.com/orobix/retina-unet

Before training, training datasets are pre-processed with the following transformations:

Gray-scale conversion
Standardization
Contrast-limited adaptive histogram equalization (CLAHE)
Gamma adjustment

 

