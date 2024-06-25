# Music Genre Classification using CNN and CRNN

## Introduction
This repository contains Python scripts for performing music genre classification using Convolutional Neural Networks (CNN) and Convolutional Recurrent Neural Networks (CRNN). The classification is based on Mel-frequency cepstral coefficients (MFCCs) extracted from audio files.

## Dataset
We used the GTZAN Genre Collection dataset, which is used for the classification of audio signals by musical genres. The dataset consists of 1,000 audio tracks, each 30 seconds long. It contains 10 genres, each represented by 100 tracks. The tracks are all 22,050Hz Mono 16-bit audio files in AU format. The genres are blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock.

The dataset has been used from Kaggle Datasets.  
[Link to the dataset](https://www.kaggle.com/datasets/carlthome/gtzan-genre-collection)

## Instructions
1. Use Kaggle Notebook to run the scripts.
2. The GTZAN Genre Collection dataset is already available on Kaggle as provided above. The dataset need not be downloaded separately.
3. Run the script `audio_features.py` to visualize the various features extracted for one of the songs from the dataset.
4. Run the script `extract_features.py` to extract MFCC features from the audio files and save them into a JSON file.
5. Run the script `train_cnn.py` to train the CNN model for music genre classification.
6. Run the script `train_crnn.py` to train the CRNN model for music genre classification.
7. After training, the scripts will output the accuracy results and genre-wise accuracy on the test dataset.

## Results
The results of the CNN and CRNN models will be displayed in the form of accuracy metrics and genre-wise accuracy on the test dataset. The overall test accuracy of the CRNN model is 79.23%. Please note that the results may vary slightly upon running the scripts again, as the `train_test_split` function randomly selects data points to split the training and testing data. Additionally, bar graphs will be generated to visualize the genre-wise accuracy.

## Files
- `audio_features.py`: Script to visualize the various features extracted for one of the songs from the dataset.
- `extract_features.py`: Script to extract MFCC features from the audio files and save them into a JSON file.
- `train_cnn.py`: Script to train the CNN model for music genre classification.
- `train_crnn.py`: Script to train the CRNN model for music genre classification.

## Requirements
- Python 3.x
- Libraries: `numpy`, `librosa`, `matplotlib`, `tensorflow`, `keras`, `sklearn`

## Authors
- **Nilesh Singla** - [GitHub Profile](https://github.com/s-n-27)
- **Manas Jhawar** - [GitHub Profile](https://github.com/Jhawar04manas)
- **Author 3** - [GitHub Profile](https://github.com/author3)
- **Author 4** - [GitHub Profile](https://github.com/author4)

