
# Text Analysis Deep Learning Course 2023

## Overview

Welcome to the Introduction to Deep Learning course Challenge, a competition at the forefront of natural language processing (NLP) and deep learning. In this competition, participants are tasked with leveraging advanced neural network architectures to classify a diverse range of textual data into predefined categories or labels.

Participants will be provided with a dataset comprising textual descriptions of advertising campaigns. The data was scrapped from its source.

The goal is to develop robust deep learning models capable of accurately categorizing these texts into multiple classes, showcasing a model's ability to understand and generalize patterns in unstructured textual information.

To foster innovation and performance, participants are encouraged to explore state-of-the-art deep learning techniques, including all techniques shown in class or more. Additionally, creativity in feature engineering, model architecture design, and ensembling strategies is highly valued.

Evaluation will be based on the classification Area under the Curve (AUC) of the models on a held-out test dataset, emphasizing both precision and recall across the diverse set of classes.

The students with top-performing models will be presenting their solutions in front of all their colleagues. The other solutions will not be neglected and will be evaluated by the lecturer. The students will be asked to specify and understand their design choices, hyperparameter choices, and especially the pre-processing steps.

## Start
- Dec 14, 2023

## Close
- Jan 12, 2024

## Description

Students can use any deep learning tool or technique, including the choice between R & Python or even a combination of both.

All pre-processing used must be explained for the final submission file.

## Evaluation

Submissions are evaluated on the Area under the ROC Curve (AUC) between the predicted probability and the observed target.

## Submission File

For each ID in the test set, you must predict a probability for the TARGET variable. The file should contain a header and have the following format:
```
ID,TARGET
2,0.05
5,0.15
6,0.952
etc.
```

## Dataset Description

An online platform, referred to as 'Kickstarter', enables individuals to seek support for a variety of endeavors such as creative projects, artistic pursuits, and journalistic ventures. During the creation of a funding campaign, creators provide a concise summary describing their project to potential supporters.

The dataset comprising these project summaries was collected from 'Kickstarter'. The summarized content used for analysis spans a period from 2009-04-21 to 2016-03-14. Each campaign's outcome—whether it achieved its funding goal or not—is known.

The data was collected by scrapping the platform data and was split randomly between train and test with no other pre-processing.

## Files

- `train.csv` - the training set
- `test.csv` - the test set
- `sample_submission.csv` - a sample submission file in the correct format

## Columns

- `state` - Target variable: was the campaign successful (1) or not (0).
- `blurb` - campaign description.
- `created_at` - date of creation of the campaign.
- `id` - unique identifier of the campaign.
