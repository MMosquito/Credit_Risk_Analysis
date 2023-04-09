# Credit_Risk_Analysis

## Overview

The purpose of the Credit Risk Analysis is to help predict credit card risk using a credit card dataset from a peer-to-peer lending services company named LendingClub. The various machine learning models used were four different samplings and two classifiers. 

## Results (Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.)

### Naive Random Sampling
    * 64% (0.6398437216722869
    * <img width="561" alt="NaiveRandomSamplingAccScore" src="https://user-images.githubusercontent.com/14171474/230792952-b1132b7d-f04d-4f20-a997-01abf185f815.png">

    
### SMOTE Oversampling
    * 62% (0.6216172933512213)
    * <img width="577" alt="SMOTEOversamplingAccScore" src="https://user-images.githubusercontent.com/14171474/230792965-959758a8-6a9d-458c-8332-c82bdb3430e8.png">

    
### Undersampling
    * 53% (0.5293026900499977)
    * <img width="576" alt="UndersamplingAccScore" src="https://user-images.githubusercontent.com/14171474/230792974-573c30a2-156b-4543-b9a5-c84262b72015.png">

    
### Combination (Over and Under) Sampling
    * 64% (0.6357786318898034)
    * <img width="598" alt="CombinationAccScore" src="https://user-images.githubusercontent.com/14171474/230792978-0d070e4e-1f77-4385-9c81-52224480af1b.png">
    
### Balanced Random Forest Classifier
    * 79% (0.7877672625306695)
    * <img width="562" alt="BRCAccScore" src="https://user-images.githubusercontent.com/14171474/230793200-37776aac-a6e3-4595-ad41-0eda20762e12.png">


### Easy Ensemble AdaBoost Classifier
    * 93% (0.925427358175101)
    * <img width="567" alt="AdaBoostAccScore" src="https://user-images.githubusercontent.com/14171474/230793194-17725cc3-1609-4707-9e01-14ebfc6f9e1a.png">


    

## Summary 

The results of the machine learning models conclude that the Undersampling is the least accurate score at 53%.  The model most most accurate is the Easy Ensemble AdaBoost Classifier at 93%. 


