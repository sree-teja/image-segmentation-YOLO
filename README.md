# YOLOv8 Semantic Segmentation Project

## Overview

This project successfully trains a semantic segmentation model using YOLOv8. It covers comprehensive data annotation guidelines, streamlined model training steps, and an efficient model validation process.

## Dataset

*   Utilized a duck dataset from Open Images Dataset V7.
*   Dataset consists of images paired with binary masks, where white pixels indicate the location of ducks.
*   Dataset available in Open Images Dataset V7.

## Data Annotation

*   **Tool:** CVAT ([cvat.ai](http://cvat.ai)) was used for image annotation.
*   Annotations were exported in "Segmentation Mask 1.1" format.

## Data Preprocessing

*   The Python script (masks_to_ploygon.py) converts binary image masks into the format required by YOLOv8.

## Training

1.  Create a PyCharm project and install dependencies.
2.  Edit `config.yaml` to specify the correct path to your data directory.
3.  Run `train.py` to start training.

## Model Validation

1.  Copy training results to Google Drive and download.
2.  Analyze training and validation loss plots, aiming for decreasing loss.
3.  Evaluate prediction images.


