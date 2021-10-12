# Deception-Detection
Detecting Falsehood in Courtroom Trials using Deep  Learning

Dataset Used: Real life trial data collected during a series of experiments at Michigan (http://web.eecs.umich.edu/~zmohamed/PDFs/Trial.ICMI.pdf)  

The dataset can be downloaded by requesting the authors https://web.eecs.umich.edu/~mihalcea/index.html  

To download/test a sample video form Real Life Trial Data, a sample video is present with name trial_lie_026.mp4.
 
 


## Step 1

pip install -r requirements.txt


## For inference 

Put the path of video in the predict.py file and run

python predict.py

## For Training the Bag_of_Lies Data

1- Put the dataset in the root directory of your project  

2- python clean.py  

3- python train.py

## Models

Pretrained models are available in Models Folder

## Accuracy, Precision, Recall Analysis

Run the custom files in Notebooks Folder
