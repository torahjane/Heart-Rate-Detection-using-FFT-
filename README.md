
# Heart Rate Detection using FFT

## Overview

This project simulates a physiological signal and estimates heart rate using signal processing techniques.

## Features

* Signal simulation (heart + respiration)
* Noise addition
* Signal filtering (moving average)
* Frequency analysis using FFT
* Heart rate estimation in BPM

## Tech Stack

* Python
* NumPy
* Matplotlib

## Methodology

1. Generate synthetic biosignal
2. Add Gaussian noise
3. Apply smoothing filter
4. Perform FFT
5. Extract dominant frequency
6. Convert to BPM

## Output

* Estimated heart rate (~72 BPM for 1.2 Hz signal)
* Time-domain and frequency-domain plots

## Future Improvements

* Use real ECG datasets
* Apply band-pass filters
* Integrate machine learning for classification

## Author

Torah Jane
