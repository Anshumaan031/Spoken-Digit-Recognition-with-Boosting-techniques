# Spoken-Digit-Recognition-with-Boosting-techniques
Objectvice:</br >
Read the audio using any library. File formats in .wav which can be read using any audio library. Extract the STFT features from the audio </br >
The Short-time Fourier transform (STFT), is a Fourier-related transform used to determine the sinusoidal frequency and phase content of local sections of a signal as it changes over time.</br >
Objective is to Create Adaboost and GradientBoost Classification models for the problem of “Spoken Digit Classification”. Here we work with benchmark dataset at https://github.com/Jakobovski/free-spoken-digit-dataset. This dataset is an equivalent of MNIST digit dataset for audio.</br >
Since audio samples differ in length, STFT will have differing lengths. This can be handled in either one of the two ways. 1) Standard size of STFT features can be extracted from middle of each audio samples, then that 2D matrix can be flattened or 2) Taking average frequency across time from STFT features.
