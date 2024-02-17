# UNet for Brain Tumor Segmentation
My implementation of UNet based on https://arxiv.org/pdf/1505.04597.pdf can be extended to any image segmentation tasks. 

In this example, I am using the dataset from Kaggle: https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation. In addition, I have reduced the size of images from 256x256 to 64x64 in order to fit my model's parameters and input data in my 4GB cuda gpu.

## Required Packages
pytorch

numpy

pandas

matplotlib

PIL

glob

os

random

tqdm
