# 13. Astronomy: Cosmic Curator – Decoding Galaxy Shapes

**Stakeholders:** Abhay Upparwal, Abdul Qadir Ronak  

**Platform:** [Kaggle](https://www.kaggle.com/competitions/cosmic-curator)

**Team Size:** 1  

## The Astronomical Observatory

Welcome to the International Virtual Observatory, humanity's most advanced center for galactic research. As a member of the elite Morphological Analysis Team, you're surrounded by massive screens displaying telescope data from across the universe. The observatory has recently received an unprecedented influx of galaxy images from the latest deep-field survey, capturing over 100,000 previously undocumented galaxies. Your director has tasked your team with classifying these cosmic structures, but the volume is overwhelming for human analysis alone. The future of galactic cartography depends on automating this process with precision and reliability.

## The GalaxyVision System

Your team has been granted access to GalaxyVision, a cutting-edge computational platform specifically designed for astronomical image analysis. This system can process high-resolution, multi-wavelength imagery and extract complex visual features that distinguish different galaxy types. GalaxyVision incorporates specialized image preprocessing techniques to handle the unique challenges of astronomical data, including noise reduction, background subtraction, and normalization across different telescope observations. However, its classification algorithm needs significant improvement to match the expertise of human astronomers.

## Detailed Problem Statement

Galaxies represent some of the most complex structures in our universe, with morphologies shaped by billions of years of evolution. Edwin Hubble's classification system (the "tuning fork") categorizes galaxies primarily as elliptical, spiral, or irregular, but modern astronomy recognizes many more nuanced variations:

Your challenge is to develop a sophisticated machine learning model that can identify these morphological types from telescope images. The model must be robust to variations in image quality, galaxy orientation, redshift effects, and the presence of nearby objects. It should extract meaningful features that astronomers use for classification, such as bulge-to-disk ratio, spiral arm tightness, presence of bars or rings, and signs of interaction.

The classification system you develop will be integrated into the next generation of astronomical surveys, helping scientists understand galaxy formation and evolution across cosmic time. It will also enable researchers to identify rare or unusual galaxies that merit further investigation with more powerful instruments.

## Dataset

- **Source:** [Kaggle](https://www.kaggle.com/competitions/cosmic-curator)  
- **Format:** JPG images of galaxies (each image is a few hundred pixels wide, with 3 color channels)  
- **Classes:** Multiple galaxy types based on morphological classification  
- **Size:** 916 labelled images  
- **Labels:**  
  - 0: SPIRAL  
  - 1: ELLIPTICAL  
  - 2: UNCERTAIN  
- **Characteristics:** Images vary in resolution, contrast, and background noise, reflecting real-world astronomical data collection challenges  

## Submission Format

- Csv file in the format (2 columns: asset_id, GalaxyType)  

## Technical Challenges

Your model must address several specific technical challenges:

- Distinguishing subtle differences between similar galaxy types  
- Processing images with varying levels of detail and quality  
- Extracting meaningful features that correlate with astronomical classification criteria  
- Achieving high accuracy while maintaining computational efficiency  

## Judging Criteria

Models will be evaluated on a held-out test set of galaxy images with hidden labels. The primary metric is classification accuracy (or macro-averaged F1-score to account for class imbalance). In other words, how many galaxies are correctly classified into the right category. The highest-scoring model (with most correct classifications) wins the contest.