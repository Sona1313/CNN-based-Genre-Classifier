# CNN-based-Genre-Classifier
Dataset-used-:-https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
Objective: To classify 30 sec audio files by genre using TensorFlow and Librosa. To classify these audio samples in .wav format, we will preprocess them by calculating their MFCC, which is a temporal representation of the energy variations for each perceived frequency band. In this case, we are choosing 13 bands. For improved modularity and clarity, we will create a dictionnary of MFCCs and associated labels in a separate json file.
