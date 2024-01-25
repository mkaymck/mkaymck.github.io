---
layout: page
title: Machine Learning Translator for American Sign Language
description: MCUNet image classification
---

# Image Classification for Sign Language Translation

I led my MIT Breakthrough AI team to work in collaboration with IBM Watson AI. The Watson AI team had developed an MCUNet model with their massive dataset of American Sign Language (ASL) images, which had a classification accuracy of 0%. I needed to improve the ability of our MCUNet model to translate pictures of ASL letters into text. I determined that the reason for poor model performance was that the original dataset contained images of neatly positioned hand signs with a blank white background, which is not representative of the realistic use scenario for this model. It is aimed at translating real life images where lighting can differ, there are varying skin tones and nail colors, different angles, etc. Since we had a limited amount of time but more people, I decided to try 2 options. One was to build a new dataset of real life pictures of ASL letters from scratch. The other option, which I coded, was to apply PyTorch transformations to the original dataset to diversify it. This included slight image rotation, horizontal flip to accommodate for left/right-handed signing, Gaussian blur for fast hand movement or poor image quality, and color jitter for varying skin tones/painted nails. I then evaluated the model with a confusion matrix. My transformations improved the model accuracy by 16%. Future work would involve finishing the realistic database for model training, as well as integrating images of ASL words, not just letters, so it can eventually be used for convenient, real time translation.
