---
layout: page
title: Convolutional Neural Networks for Melanoma Detection
description: Advancing Personalized Medicine through Machine Learning
---

# Customizing Google Inception v3

Can we use image detection models to aid in the diagnosis of medical conditions with visual indicators? One example is Melanoma, the most serious form of skin cancer. It’s important to properly distinguish it from other skin cancers, and leveraging AI tools may enable faster, more cost effective, potentially more accurate, and remote diagnosis compared to today’s standard practice. I sought to explore this opportunity for improvement by using CNNs to determine if an image of a skin lesion is melanoma or not.

I chose the Google Inception v3 CNN to detect melanoma in images of skin lesions. I chose this model in particular because it scales up neural nets without increasing computational cost, under the impression that I would have a large dataset. However, after I finalized my dataset I realized it was really small so this project didn’t benefit much from the Inception advantage. I procured a dataset that contains images of skin lesions from females 18-24 using the ISIC database. I then trained and tested the Inception v3 CNN on this data. The Inception v3 had an average of 52% accuracy, which has lots of room for improvement. It’s essentially the same as random chance. My first next step would be to find a much larger database for this patient group. Another future step would be trying a ResNet model instead, because while Inception focuses on computational cost, ResNet focuses on computational accuracy.
