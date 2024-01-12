# Noise Filtration Project


This project focuses on implementing a noise filtration algorithm in Python without using external libraries. The goal is to remove unwanted noise from audio signals, providing a cleaner audio output.

## Overview

The noise filtration is achieved through two main methods:

1. **Frequency Domain Filtering:**
    - The audio signal is converted from the time domain to the frequency domain using a custom implementation of the Fast Fourier Transform (FFT).
    - The magnitudes of the audio and noise spectra are calculated.
    - A threshold-based approach is used to identify and filter out noisy frequency components.
    - The filtered audio is reconstructed using the Inverse FFT.

2. **Wiener Filtering (Optional):**
    - An alternative method using Wiener filtering is provided but commented out in the code.
    - The Wiener filter estimates the clean signal by considering the power spectral densities of the signal and noise.

## Usage

- Clone the repository:

   ```bash
   git clone https://github.com/WiTheR60334/Noise-Filtration.git
   cd Noise-Filtration

- Replace 'final.wav' and 'finalnoise.wav' with your audio and noise file paths.
- Adjust parameters such as threshold according to your audio characteristics.


## Screenshots

![Screenshot 2023-11-20 215142](https://github.com/WiTheR60334/Noise-Filtration/assets/115364885/074fbe5c-28ef-4b0c-8895-f50813349ef4)

- Blue is the audio with noise in it and Orange is the audio without noise.
- The denoised audio is visualized using Matplotlib to compare the original and filtered signals. 

