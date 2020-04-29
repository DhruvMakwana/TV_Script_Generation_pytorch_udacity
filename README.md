# TV_Script_Generation_pytorch_udacity
This project is a part of deep learning nano degree at Udacity.

## Project overview:
In this project, you'll generate your own Seinfeld TV scripts using RNNs. You'll be using part of the Seinfeld dataset of scripts from 9 seasons. The Neural Network you'll build will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.
Dataset can be found [here](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv)

## Project Instructions:

1. Clone the repository and navigate to the downloaded folder.

    `git clone https://github.com/HectorBudielE/udacity-tv-script-generation.git`
	
2. Make sure you have already installed the necessary Python packages according to the requirements.txt file.

3. Open a terminal window and navigate to the project folder. Open the notebook and follow the steps.

    `jupyter dlnd_tv_script_generation.ipynb`
    
    
## Contents
1. Get the Data
2. Explore the Data
3. Implement Preprocessing Functions:
    * Lookup Table
    * Tokenize Punctuation
    * Pre-process all the data and save it
4. Build the Neural Network
    * Check Access to GPU
    * Input Batching
    * Test the Dataloader
    * Model
    * Defining Forward and Backpropagation
5. Neural Network Training
    * Train Loop
    * Hyperparameters
    * Training
6. Generate TV Script
    * Generate Text
    * Generate a New Script
    
