# EEG-Based Analysis of Alpha Brain Activity During Eyes-Open and Eyes-Closed Conditions

## Overview

This project analyzes EEG recordings to compare alpha-band (8–12 Hz) brain activity during eyes-open and eyes-closed conditions.

The analysis was performed using EEG recordings from the Unicorn BCI Core-8 EEG Datasets. The project focuses on EEG preprocessing, Power Spectral Density (PSD) estimation, alpha-band power extraction, and comparison of alpha activity between the two experimental conditions.

## Dataset

The project uses EEG recordings from the Unicorn BCI Core-8 EEG Datasets.

- Sampling frequency: 250 Hz
- Number of EEG channels: 8
- Channels: Fz, C3, Cz, C4, Pz, PO7, POz, PO8
- Conditions analyzed: Eyes Open and Eyes Closed

Dataset source:
https://github.com/unicorn-bi/Unicorn-BCI-Core-8-EEG-Datasets

## Analysis Pipeline

1. Load eyes-open and eyes-closed EEG recordings
2. Identify and validate the eight EEG channels
3. Check EEG data quality
4. Visualize raw EEG signals
5. Apply a 0.5–40 Hz Butterworth bandpass filter
6. Apply a 50 Hz notch filter
7. Estimate Power Spectral Density using Welch's method
8. Extract alpha-band power from 8–12 Hz
9. Compare alpha power between eyes-open and eyes-closed conditions
10. Calculate descriptive statistics and visualize the results

## Technologies Used

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- Jupyter Notebook

## Key Result

Higher mean alpha power was observed during the eyes-closed condition compared with the eyes-open condition across all eight EEG channels in the recordings analyzed.

## Repository Contents

- `EEG_Alpha_Power_Analysis_GitHub.ipynb` — complete EEG analysis notebook
- Results and additional project documentation will be added to this repository.

## Author

**Shravan Bhagwan Patil**  
CSE (Cloud Computing)  
Vishwanath Karad MIT World Peace University
