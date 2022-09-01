# MusAIc
A classification model that tags songs based on their features


## 1. Prerequisite
- Download annotation and mp3 file data from https://mirg.city.ac.uk/codeapps/the-magnatagatune-dataset (MagnaTagATune)
- Install 'Librosa' to process music data: https://librosa.org/doc/latest/install.html/ (Librosa)


## 2. Development Practice
- Create **NEW** notebooks to run the following steps for proper visualization and viewing purposes. 

## 3. Executing Steps 
- Step 1(optional): run 'Librosa Sandbox.ipynb' to experiment with data

- Step 2: run 'Feature Extraction.ipynb' to make sure all files are in proper format
    - extract the mel spectograms from the songs
    - Mel Spectrogram = frequency domain representation of audio

- Step 3: run 'Magnatagatune.ipynb' to load X and Y vectors of songs to use for models

- Step 4: run 'Model Training.ipynb' to train models and view tagged songs. 
