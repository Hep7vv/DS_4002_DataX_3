# DS_4002_DataX_3
Image Processing Project

Data:
create a folder called project3. in the folder, upload the zip file and create the ipynd file to write the code.
create a folder called data in the porject 3 file. run the code first two lines of code in the ipynd file to transform the zip file inot images. A folder will be create in the data folder which contains each letter and all the images assoicate with it.

## Contents
This repo contains data, results, and information regarding image recognition of sign language letters
### including: 

Readme - explanation of the repository

Licensing - explans the terms under which this repository can be cited

Scripts - contains all source code for the project, scripts used with explanation of commands

Data - Contains all data for the project and a Data Appendix outlining analysis and variables for each respective dataset

Output - contains all output generated from data analysis including tables and figures 

## Section 1: Software and Platform

### Software:

Python: 3.10 via Google Colab

Python: 3.10 via Jupyter Notebook

### Addons: 

Pandas

Numpy

matplotlib

sklearn

- confusion_matrix
  
- classification_report

tensorflow

- ImageDataGenerator
- ResNet50
- Sequential
- GlobalAveragePooling2D
- Dense
- Dropout

seaborn

zipfile
random
shutil

pathlib

 - path

### Platform:

Windows 10

## Section 2: Map of Documentation

README

LICENSE

SCRIPTS

- ASL_Final_Code.ipnyb

DATA

- A
- B
- C
- D
- E
- F...ETC
- Data Appendix.pdf
- american-sign-language-letters-subdir.zip
  
OUTPUT

- ALSImages.png
- New ASL numbers.jpg
- training_vs_validation_eightepoch.png
- training_vs_validation_smallepoch.png
  
REFRENCES.md

## Section 3: Reproducing Results

Step 1: importing addons

download and import the addons listed above and test to ensure they are operating as expected

Step 2: import Image data

define the zip file containing the sign language images and extract it to a folder. Establish Directories for the source, training, and output. move the image files to test and train validation folders. load raw images and split before cleaning. run preproccessing (convert images to grayscale and normaize the scale of pixels into 64x64.

Step 3: Train Model

using tensorflow import associated addons to create a lightweight CNN model. when defining the model set it to 64 x 64 and single channel color. compile the model. to train set the patience and epochs to a number that makes sense for available time, more patience and more epochs generally leads tot greater model accuracy. 

Step 4: Test Model

once the model is trained it can be evaluated on the test set created in step 2 and the final test accuracy can be determined. 
