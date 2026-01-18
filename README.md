# Birdcall-Identification-Audio-Analysis

train.csv contains information about the audio files available in train_audio. It contains 21,375 datapoints in 35 unique columns.
test.csv contains only 3 observations (the rest are available in the hidden test set).

Note: The TRAIN data has 1 labeled bird species per recording. However, in nature usually you can hear tens (even hundreds) of birds in one go, so in TEST set we need to predict 0, 1 or multiple species for one recording. Because of this, in TRAIN we have species column - or primary_label - (main bird), secondary label (other birds heard) and background (background noises, other birds etc.)

dataset:
https://xeno-canto.org/

