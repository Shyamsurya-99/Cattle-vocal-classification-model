# Cattle-vocal-classification-model
# Audio Preprocessing and Visualization

This repository contains a Jupyter notebook for preprocessing audio files by reducing noise and visualizing the results through spectrograms and waveforms.

## Features

1. **Noise Reduction**: Cleans audio files using the `noisereduce` library.
2. **Visualization**: Generates and displays spectrograms and waveforms for raw and preprocessed audio.
3. **File Management**: Organizes audio files into categories and counts files in each category.

## Usage

1. **Setup**:
   - Install required libraries:
     ```bash
     pip install librosa noisereduce soundfile matplotlib numpy
     ```
   - Ensure your directory structure matches the expected input and output paths.

2. **Running the Notebook**:
   - Preprocess audio files by loading, cleaning, and saving them.
   - Visualize audio data by plotting spectrograms and waveforms.
   - Count the number of files in each category.

3. **Example**:
   ```python
   # Example paths
   raw_audio_path = 'path/to/raw_audio.wav'
   preprocessed_audio_path = 'path/to/preprocessed_audio_clean.wav'

   # Plot spectrograms and waveforms
   plot_spectrograms_and_waveforms(raw_audio_path, preprocessed_audio_path)
