# lyrics_topic_models
Topic Modeling of Music Lyrics

This notebook uses topic modeling on rap lyrics to that we can investigate differences between East Coast and West Coast rap and its legendary rivalry.  Additionally, we will ask whether any differences in gender between Male and Female rappers who were a part of this rivalry.  The objective here is not the rivalry or the regrettable violence and unfortunate lives lost but rather what we can learn about differences in styles, themes and word choice

Running this notebook:

1. Get the data
    * Download the 2 zip files from here : https://www.kaggle.com/artimous/every-song-you-have-heard-almost
    * Create a directory : c:\datasets\lyrics\
    * Unzip the 2 ZIP files here so that you should have two CSV files : Lyrics1.csv, Lyrics2.csv
2. Get the required packages (you can do this either with a virtual environment or default Python environment)
    * Default Python environment : 
        * Open the command line and change directory to where the notebook exists
        * Run the following : 
            * pip install -r requirements.txt
            * jupyter notebook
    * Virtual environment : 
        * Open the command line and change directory to where the notebook exists
        * Run the following : 
            * python -m venv lyrics
            * lyrics\Scripts\activate
            * pip install -r requirements.txt
            * jupyter notebook