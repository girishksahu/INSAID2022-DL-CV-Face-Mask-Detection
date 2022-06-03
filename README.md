# INSAID2022-DL-CV-Face-Mask-Detection
INSAID 2022 Deep Learning CV Term Project
# Project Description
## Introduction
- Your client for this project is a tech startup.
    - Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization.
    - Therefore, to protect each other, every person should wear a face mask properly when they are outdoors. However, most selfish people won’t wear the face mask properly for so many reasons.
    - To overcome this situation October Tech is working on a project to automatically detect whether a person is wearing a mask or not.
    - The researchers are building a model to detect people wearing masks, not wearing them, or wearing masks improperly.

## Current Scenario
- The detection of face masks can help prevent Covid-19 spread.
- Analyzing whether a person is wearing a mask properly is a manual task.
- However, Designing a computer program to do this turns out to be a bit trickier.
## Problem Statement
The current process suffers from the following problems:
- It is very difficult to identify whether all persons are wearing masks in a proper way.
- It is tedious to hire a person to inspect individually.
- This process is slow and time-consuming.

## Project Task
* Project task is to automate the process of identifying whether a person is wearing a mask properly.
* This model should return high accuracy.

## Project Deliverables
- Deliverable: **Face Mask Detection.**
- Machine Learning Task: **Image Classification**
- Target Variable: **Category**
## Evaluation Metric
* The model evaluation will be based on the Accuracy score.
# Data Description
* The dataset contains images of the different people with and without masks.
* The dataset contains images of 3 categories, people wearing masks, not wearing, incorrectly wearing.
* This is the data that we have to predict for future images.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 682 images and 3 label categories.

## Test Set:
* The test set contains 171 images.
* The test set doesn’t contain the label categories.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Wearing Mask**   | 0    |
|02| **Not Wearing**   | 1       |
|03| **Not Wearing Correctly** | 2   |
