# VisionSegmentation

This repository discusses image and video segmentation. Basically, there are two categories of segmentation namely, instance segmentation and semantic segmentation.

-Semantic Segementation: the model detects the objects and start segmenting process where it assume different objects of the same category the same. A well-known model of this task is U-net. 

-Instance Segementation: the model detects the objects and start segmenting process where it assume different objects of the same category unique. A well-known model of this task is Mask RCNN.

Update on Sep 2023: to use Mask RCNN, you may face the error "module 'numpy' has no attribute 'bool'" for line "results = network.detect([image], verbose=0)". The error stems from new version NumPy. Simply uninstall the NumPy and install the older versions as below:
