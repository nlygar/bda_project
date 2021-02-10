# Speech Emotion Recognition (SER) using Deep Neural Network


## Project Objective 
<p align="justify">
Humans have the natural ability to use all their available senses for maximum awareness of the received message. The emotional detection is natural for humans but it is a very difficult task for machines.
In this project,  a simple emotion recognizer is build from speech data using a deep neural network.
 </p>

## Pre-requisites

* Python 3.5 
* librosa
* keras 
* tensorflow
* scikit-learn
* numpy
* seaborn
* matplotlib
* pandas

## Installing dependencies

Note: You can skip this step, if you have the  packages already installed.
Dependencies are in the requirements.txt file.

Install the dependencies by running : 

```
  pip3 install -r requirements.txt 
```

## Directory Structure

* `src/` : Package folder which contains all the code files 
* `data/` :  Contains the speech files 
* `models/`: Contains the saved models which obtained best accuracy on test data.


## Data

* RAVDESS 
    * Speech emotions: 7 (calm, happy, sad, angry, fearful, surprise, disgust)
    * North American accent
    * Source: https://smartlaboratory.org/ravdess/

* Crema-D
    * Speech emotions: 6 (Anger, Disgust, Fear, Happy, Neutral, and Sad)
    * African American, Asian American, Caucasian American, Hispanic American, and Unspecified accent
    * Source:  https://github.com/CheyneyComputerScience/CREMA-D
    
* SAVEE
    * Speech emotions: 7 (common,anger, disgust, fear, happiness, sadness, surprise, neutral)
    * English accent
    * Source: http://kahlan.eps.surrey.ac.uk/savee/Database.html

* TESS
    * Speech emotions: 7 (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral)
    * English accent
    * Source: https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess
