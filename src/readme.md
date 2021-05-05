In this folder we added the codes to do feature extraction, build and train models and a demo script.

A. DEMO.ipynb: 
- the user have to define the variable model_path with the path to the .sav file of the selected model
The demo follows the next steps:
1. Import necessary libraries
2. Import selected model
3. Import data (from a Dropbox folder: https://www.dropbox.com/s/ywf59s5uljcotwd/GTZAN.zip?dl=1)
4. Selects a song 
5. Perform feature extraction (MFCCs)
6. Evaluate the song and plot the results. 

B. ML - Visual Comparison + Audio feature Extraction + Build and Train Classical Models + Classification Repports.ipynb: 
- the user has to be careful to change all the variables that lead to the files.

This scripys follows the next steps:
1. Import necessary libraries
2. Visual Comparison between different features 
  a. Plot Mel spectrogram, MFCC, chroma for each genre. 
3. Creates the .json file with the MFCC features 
4. Classical Models
  a. Build models
  b. Train and save models
  c. Select saved model and plot results (Confussion Matrix and Classification Report)
  
C. 
