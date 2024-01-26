---
layout: page
title: Predicting Antibiotic Resistance
description: Generic prescriptions < thoughtful, personalized treatments
---

# Advancing Women's Health through Machine Learning

Urinary tract infections (UTIs) are the most common outpatient infections, with a lifetime incidence of 50−60% in women according to the NIH1. This bacterial infection strongly interferes with everyday life. Recurrent UTIs are associated with symptoms of anxiety and depression as well as financial burden, an inability to participate in activities or focus, and reduced quality of life.

Why use machine learning to predict antibiotic resistance based on the present organism? Machine learning is a great tool for personalized medical care. Extracting important information from massive amounts of data saves time and can produce useful insights. Deep learning is quite a “black box”, which is why simpler models tend to be used for clinical data. That way, clinicians with less of a computational background still know what’s being done with the medical data.

The bulk of my project involved cleaning and preparing the data. Then I built a simple decision tree model and evaluated performance with a confusion matrix. To preserve the integrity and privacy of this secured patient data, I decided to shuffle the data.
The model accuracy on the real data was 65.9%, and 69.5% on the shuffled data. These are promising results, and I believe there are good opportunities to explore how to improve prediction accuracy. For example, accounting for past antibiotic use.
