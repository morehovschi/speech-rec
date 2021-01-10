# Single-word speech recognition on the Tensorflow Speech Recognition dataset
This is one of the 4 networks trained as part of a larger project on speech recognition in CS 497: Advanced Perception at Colby College. Full project write-up: https://wiki.colby.edu/display/~moreho21/Marius+and+Caleb%27s+CS+497+Project+2%3A+Convolutional+and+Recurrent+Speech+Classification

This repository only contains a training and evaluation notebook for the network we deemed best (in terms of final accuracy and training & inference time) – the Convolutional-LSTM network trained on Mel-spectrograms. For a demonstration, open the notebook and only run cells starting at section 4: Testing on own voice commands.

### Requirements
This project requires an IPython kernel, the SoX package (`brew install sox` or  `sudo apt-get install sox`), and the following Python packages: tensorflow>=2.0, librosa, scipy, matplotlib.
