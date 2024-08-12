# Musical-Composer-Classification
In this project we investigate the use of various deep learning techniques to classify musical compositions from well known composers, Bach, Beethoven, Chopin and Mozart. The goal is to construct a robust model capable of properly identifying the composer when presented with a musical piece.

The Pretty MIDI Python library was utilized to extract key features from the provided MIDI files, including note pitches, note velocities and tempo changes. These features serve as the foundation for capturing complex patterns within the MIDI files by employing a hybrid neural network architecture. The architecture combines Convolutional Neural Networks (CNNs) for their ability to extract temporal features and Long Short Term Memory (LSTM) layers for their ability to capture long term dependencies and sequential patterns often found in music.

This project showcases the potential of deep learning to understand and categorize complex artistic data, paving the way for new explorations and innovations at the intersection of artificial intelligence and musicology.
