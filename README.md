AudioClassifier2.ipynb is the updated project, we have left the previous one (AudioClassification.ipynb) for reference.
 
 # AudioClassifier
 
Abstract:

This project aims to build a machine learning model to accurately identify capuchin bird calls on a virtual notebook using tinyML. We aim to collect and capture data for training, transfer learning, re-training, deploying to a simulation environment.

Dataset:

This model will be trained on the Capuchin bird sounds dataset, which contains the characteristic sound of capuchin birds. Each audio file is 3 seconds each in length. Any soundbites that contain pure silence will be discarded.

Waveforms:

Sound files are converted to a waveform representation. This waveform representation converts the pressure variations of sound waves into a pictorial graph which is easier to convert to spectrograms, which is required for feeding into the model.

Spectrograms:

We will transform the audio data into an audio spectrogram representation. This will create a 2D representation of the audio signal’s frequency content over time.

