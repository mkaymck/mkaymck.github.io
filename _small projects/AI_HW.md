---
layout: page
title: Sliding Window Framework for Precision Cancer Care
description: Deep Learning to Classify Whole Slide Images
---

# Cancer Detection in Whole Slide Images

A sliding window framework creates a small window of fixed size in the top-left corner of the image. The window progresses sequentially across the image. At each stop, the model within the window analyzes the content inside it. This project uses a sliding window framework for the classification of high resolution microscopy images as chromophobe renal cell carcinoma, papillary thyroid cancer, or clear cell. The primary task of this project was to demonstrate that I can successfully run a complex framework model with medical images, and optimize it by testing different parameters (specifically, target level, output size, and stride) for extracting and classifying tissue patches from the whole slide images.
I ran the framework with a variety of parameter settings, particularly with target level, output size, and stride. The optimal parameter changes resulted in a 26.5% increase in model performance. Future work would involve testing this in an HPC environment such that many more parameter options and combinations could be tested.
