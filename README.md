FPN
Pytorch 1.  implementation of Feature Pyramid Network (FPN) for Object Detection with Faster RCNN and Resnent

## Introduction

This project is based on[pytorch implementation of faster r-cnn](https://github.com/jwyang/faster-rcnn.pytorch). Hence, it also has the following unique features:

## Benchmarking

We benchmark our code on  coco. Below are the results:

1). MSCOCO (Train/Test:, scale=, ROI Align)

model    | GPUs | Batch Size | lr        | lr_decay | max_epoch     |  Speed/epoch | Memory/GPU | mAP 
---------|-----------|----|-----------|-----|-----|-------|--------|--------
Res-101    | 2 2080 Ti | 24| 1e-2 | 10  | 12  |   |   | 

