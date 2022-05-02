# roBach_Music_Classification

This is a school group project to train models to accurately identify instrumental ensembles of a song using MusicNet Classical Music Dataset. The slide deck can be found in this repo.

We have four folders in this repo:

- <b> data folder: </b>
  - Features we extracted from the wav and midi files were exported to csv and saved in this folder 
  - Wav, Midi, Metadata, NPZ Files dataset (21 Gigabytes) can be found at this <a href="https://www.kaggle.com/imsparsh/musicnet-dataset/code">kaggle link</a> and in <a href="https://drive.google.com/drive/u/1/folders/1f4AakoH7RQ51WqieexWNDDhywJ0sH3vC">our google drive link </a>.
  - EDA Plots done in google collab were saved in both google drive and github. Not all the plots could not be done in github due to 21gb data size.

- <b> scripts folder: </b>
  - Data Preprocessing : Extraction and Feature Engineering
    - Link to <a href="https://colab.research.google.com/drive/1I5xCF_rOZxNuKLmVRlfRIbiMJtHtykwm?authuser=1#scrollTo=pEGGz1GZCyCD"> Google Collab Data Preprocessing File </a> : This runs the Data Extraction on larger files saved in google drive. Please contact Ziling Huang if you are a grader and need access to mount the google drive and the google collab file. Instructor Cornelia Ilin has been given access.
    - Data Extraction and Feature Engineering.ipynb saved in github. You can view the same code here as well but some of the code only runs in google collab.
    - 3 Datasets were created :                    
      - MIDI Features only : Feature Engineering Performed 
      - Spectral Features from Wav Files
      - Wav and MIDI combined
              
  - Exploratory Data Analysis : Distribution and Correlations 
    - Link to <a href="https://colab.research.google.com/drive/1xwEuh2z3gEDekdTmc5qNzagcIhIRpBBl?authuser=1#scrollTo=qZgc6bu8FFVi"> Google Collab EDA File </a> : This runs the EDA on larger files saved in google drive. Please contact Ziling Huang if you are a grader and need access to mount the google drive and the google collab file. Instructor Cornelia Ilin has been given access.
    - Exploratory Data Analysis.ipynb saved in github. You can view the same code here as well but some of the code only runs in google collab.
    - NPZ Data Exploration
    - WAV files Exploration
    - MetaData Exploration
    - MIDI Data Exploration

  - Model Tuning, Validation and Testing :
    - Refer to "Model Consolidation.ipynb" for consolidated training models and 5-fold cross validation on development set.
    - Refer to "Model Test Set Evaluation.ipynb" for testing model performance on test data.
    - Evaluation Criterion : F1-Score
      - Naive Bayes (Baseline)
      - Decision Tree
      - Logistic Regression
      - Random Forest
      - Support Vector Machines
      - Neural Network
  - P.S. Do not run individual models in Individual Models folder

- <b> output folder: </b>
    - Saved images of our EDA plots are here
    - Test and Development Set Results are saved here

- <b> literature folder: </b>   
    - Our readings and references to current research in this domain 
