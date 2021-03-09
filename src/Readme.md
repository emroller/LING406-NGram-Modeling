# LING 406 Assignment 2: N-gram Language Modeling

This program uses n-gram language modeling to predict whether a given sentence is written in English, French, or Italian. It uses a bigram model to train the predicting program on three separate input files, one written entirely in each language, and predicts the language of each line in a test file using the same bigram model. One predictor uses a letter bigram model with LaPlace smoothing, and the other two use a word bigram model with either LaPlace or Good-Turing smoothing. The accuracy levels varied depending on the bigram model, but all achieved an accuracy rate of 92 percent or greater.

To run the code, perform the following steps:
  * Navigate to the directory in which the ipynb files are located
  * Ensure that your input training files are also in this directory and titled "LangId.train.LANGUAGE", with either English, French, or Italian replacing the LANGUAGE parameter. If you wish them to be located elsewhere or named otherwise, you can change the path to open the input files in the third cell (titled "Start here")
  * Similarly, ensure that your input testing and output result files are in the current directory and the input testing file is named "LangId.test". Again, if you wish to change the paths to open these files, you can do so in the third cell.
  * Run all cells in the .ipynb file. The output will be written to the solution file opened in the previous step.
