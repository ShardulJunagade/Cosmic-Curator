# Cosmic-Curator

## Overview
Cosmic-Curator is a machine learning project developed for Hackrush, the annual hackathon of IITGN. The project focuses on automating the classification of galaxy shapes using deep learning techniques. This initiative is part of the International Virtual Observatory's efforts to process and analyze an unprecedented influx of galaxy images from the latest deep-field survey.

## Problem Statement
The International Virtual Observatory has received over 100,000 previously undocumented galaxy images. Manual classification of these images is infeasible due to the sheer volume. The goal of this project is to develop a robust and precise automated system to classify these cosmic structures, aiding the future of galactic cartography.

## Model Architecture
- **Base Models**: ResNet-18, Swin-Tiny, Swin-Small, Swin-Base 
- **Modified Fully Connected Layer**: The final fully connected layer is modified to output 3 classes corresponding to the galaxy types.
- **Training Enhancements**: Includes data augmentation techniques like random horizontal flips, rotations, and color jittering to improve model generalization.

## Dataset
The dataset consists of galaxy images from the International Virtual Observatory, categorized into three classes:
- Spiral
- Elliptical
- Uncertain

## Future Work
- Extend the model to classify more galaxy types.
- Incorporate additional preprocessing techniques for better feature extraction.
- Deploy the model as a web application for real-time classification.

## Acknowledgments
This project was developed as part of Hackrush 2025, IITGN's annual hackathon. Special thanks to the organizing team and mentors for their guidance and support.

## Author
- **Name**: Shardul Junagade
- **Email**: 23110297@iitgn.ac.in
- **Roll Number**: 23110297