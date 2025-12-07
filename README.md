# ai-image-detection
Authors: Andreas Jürgenson, Richard Jaarman

## Goals
Our project addresses the problem of misinformation by aiming to create a machine learning algorithm that would be able to distinguish real photographs from AI generated images. This tool could benefit people who are less technologically aware to tell apart the fake from the real and inhibit the spread of misleading news and clickbait.

## Repository
The repository contains the notebook which includes all our training and validation code and the models code. It also shows statistics of our model The repo also has the model which was trained for 30 epochs, the report, a pn of the architecture and this readme file.

## How to use the model

1. To use the model load up the ```AIdetect.ipynb``` in your IDE.
2. Download the dataset from Kaggle and place it into the project directory under ```dataset/```
3. Install the required dependencies (If you use an AMD GPU run the second cell too).
4. If you wish you can custom select your desired batchSize,subsetSize under creating train and test sets and the number of epochs, learning rate and checkpoint path under hyperparameters.
5. Run the Jupyter notebook (It will automatically detect if you have a suitable gpu or cpu to run off of).
6. If you wish to use the model on your own images head to 'Usage example' and replace the imae path with your own image path and run the cell.
