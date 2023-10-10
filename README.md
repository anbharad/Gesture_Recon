# Gesture_Recon
Case study Gesture Recognition
Gesture Recognition via Conv3D and via Conv2D+LSTM/GRU Deep Learning Models.
# Problem Statement
Consider yourself a data scientist employed by a business that produces cutting-edge smart televisions for the home. You want to create a fun feature for the smart TV that can recognize five distinct user gestures and let people operate the TV without a remote.

Thumbs up: Increase the volume
Thumbs down: Decrease the volume
Left swipe: 'Jump' backwards 10 seconds
Right swipe: 'Jump' forward 10 seconds
Stop: Pause the movie
# Getting around the data
A small number of hundred videos that have been divided into one of the five classes make up the training data. Each video, which is typically 2-3 seconds long, is broken up into 30 frames (pictures). These films include different people acting out one of the five motions in front of a webcam, much like the smart TV will.

It should be noted that while various videos may have varying dimensions, all of the photos in a given video subfolder have the same proportions. Videos can be either 360x360 or 120x160 pixels in size, depending on the webcam that was used to record them. To standardize the movies, you will therefore need to perform some pre-processing.

