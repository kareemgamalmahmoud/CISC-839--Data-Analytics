# Lab_5 : Deep learning based end-to-end speech recognition

- The goal of this assignment is to get familiar with applications that require speech data as input.

- We would be using the torchaudio library (pip install torchaudio==0.11.0)

- Next, we would ask you to perform similar analysis on a speech dataset, i.e.


## Task 1: Basic data exploration Select one randomly sampled wav file in the given folder, perform the following analysis:

1) Print the shape of the picked waveform

2) Print the sample rate of the waveform.

3) Visualize the waveform using matplotlib

4) Create the spectrogram representation of the picked waveform and visualize it.

5) Create the MFCC representation of the picked waveform and visualize it.

## Task 2: Creating a Wav2Vec2 model that can perform feature extraction and classification.

### Wav2Vec 2.0 Model Architecture

The architecture of the final model used for prediction consists of three main parts:

- convolutional layers that process the raw waveform input to get latent representation - Z,
- transformer layers, creating contextualised representation - C,
- linear projection to output - Y.


## Task 3: Extract acoustic features and generate predicted transcript for each waveform in the given dataset

## Task 4: evaluate the performance of the trained model on the testing dataset using Word Error Rate (WER), Match Error Rate (MER)

## Task 5: check files with the worst performance and perform a simple error analysis, e.g.,

1. What are the files having worser performance,
2. And what are the potential reasons,
3. Do they share any common patterns?
