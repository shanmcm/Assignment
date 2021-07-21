# Predicting-a-wine-s-score

## Overview

Project for the *Data Science Lab: Process and methods* course at Politecnico di Torino.</br>
The proposed solution granted me second place in the final leaderboard.</br>
For a detailed explanation of the adopted apporach see the *report.pdf* file.

## Problem Description

This project consists in the prediction of a quality score associated with a wine review. Technically, a regression model capable of inferring the wine’s quality given the content of the
review must be built. </br>
The dataset contains wine reviews in tabular format. It counts 150.930 entries, each of
which referes to a review expressed by an expert on a specific wine.
Each review is characterized by both numerical and categorical attributes. A textual description is
provided as well. The quality score is indeed reported on the feature named quality. </br>
The following is an example of a record:

|Country   |Description   | Designation  |Province   | Region_1  | Region_2 | Variety | Winery| Quality|
|---|---|---|---|---|---|---|---|---|
|  US |  One of the more successful blush wines out there |  Estate Grown | California	  |Dry Creek Valley   |Sonoma| Rosè| Fritz | 37.0


Within the archive, you can find the following 2 files:
• dev.tsv (development set): a tab-separated values file containing the reviews from the development
set. This portion has the quality feature, which is used to train and validate the
model.
• eval.tsv (evaluation set): a tab-separated values file containing the reviews from the evaluation set.
This portion does not have the quality feature.
