
eye - v2 eyeDataset
==============================

This dataset was exported via roboflow.com on September 26, 2023 at 7:42 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 509 images.
Eye are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 2 versions of each source image:
* 50% probability of horizontal flip
* Random rotation of between -24 and +24 degrees
* Random brigthness adjustment of between -26 and +26 percent
* Random Gaussian blur of between 0 and 3.25 pixels
* Salt and pepper noise was applied to 10 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Randomly crop between 0 and 24 percent of the bounding box
* Random Gaussian blur of between 0 and 4.25 pixels
* Salt and pepper noise was applied to 2 percent of pixels


