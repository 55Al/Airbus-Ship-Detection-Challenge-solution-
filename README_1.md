# SegNet
SegNet is a model of semantic segmentation based on Fully Comvolutional Network.

This repository contains the implementation of learning and testing in keras and tensorflow. Also included is a custom layer implementation of index pooling, a new property of segnet.


Architecture:
*encoder decoder architecture

*fully convolutional network

*indices pooling


Description:
This repository is SegNet architecture for Semantic Segmentation. The repository of other people's segmentation, pooling with indices not implemented.But In this repository we implemented pooling layer and unpooling layer with indices at MyLayers.py.

Segnet architecture is early Semantic Segmentation model,so acccuracy is low but fast. In the future, we plan to implement models with high accuracy.(UNet,PSPNet,Pix2Pix ect..)


Usage:
train>>
python SegNet.py [--options your dataset]
