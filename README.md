# LearningFoodPreferences

This repository contains Jupyter notebooks that each implement a separate method for preprocessing food log entry names. These notebooks are in the folder "methods_notebooks." It also contains necessary data files in the folder named "data." 

Steps to Run:
1) Clone the repo by pasting this command: git clone https://github.com/aametwally/LearningFoodPreferences.git
2) Enter the local LearningFoodPreferences directory: cd ~/Downloads/LearningFoodPreferences
3) Run the notebooks in the "methods_notebooks" folder. You can run a notebook with the command "jupyter notebook LFP_Method_4.ipynb" (substitute the desired notebook name). Running all of the cells will load a sample food log (which is found in the folder "sample_food_logs"), run the food preference elicitation algorithm, and generate evaluation metrics. Note: the data files are currently stored in a folder, "data," that is separate from the one in which the notebooks are stored. The code currently assumes that the data and notebooks are in the same folder, which you can set by changing the PATH_NAME variable, and that the food logs are in a subfolder called "sample_food_logs."

The required packages are nltk, pandas, os, numpy, gensim.models, sklearn, collections, and math.

The file containing the word embeddings is too large to upload. Please access and download it from here: https://drive.google.com/file/d/1EoNIIfAhXgMaWgmrCOQkzqV2pOvKQOBN/view?usp=sharing.
