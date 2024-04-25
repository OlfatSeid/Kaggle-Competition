# Assessment of Potential Threat

## Timeline

February 6th, 2024 - Competition launched
February 20th, 2024 - Final submission deadline.
Deadlines are at 11:59 PM on the corresponding day unless otherwise noted.

## Maximum number of submissions per day

Each day you can upload up to a maximum of 20 solutions. When this number is reached in a day, you will need to wait for another day (UTC) to start to be able to upload more solutions.

## Final Private Leaderboard

You can select 4 submissions to be eligible for the final private leaderboard. These eligible submissions can be hand-select, or will otherwise default to the best public scoring submissions.

## Evaluation Metric

The evaluation metric for this competition is the [F1 Score](https://www.kaggle.com/wiki/F1_Score). The F1 score, commonly used in information retrieval, measures accuracy using the statistics precision prec and recall rec. Precision is the ratio of true positives tp to all predicted positives tp + fp. Recall is the ratio of true positives to all actual positives tp + fn. The F1 score is given by:

$$ F1 = 2\frac{PrecisionRecall}{Precision+Recall} = \frac{2TP}{2TP+FP+FN} $$

The F1 score is the harmonic mean of the precision and recall. The highest possible value of F1 is 1, indicating perfect precision and recall, and the lowest possible value is 0, if either the precision or the recall is zero.

The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other.

## Submission Format

Your submission file should contain a header two columns: ID and Class. Please see the sample submission provided to verify the format of the submission file that you need to upload.

## Description

### Context

Network security is important for home networks as well as in the business world therefore a solid network security system helps catch attackers (hackers) before they do real damage to a network and reduce the risk of data loss, theft and sabotage.

### Competition

In this competition you will have to predict which are the malicious attempts or attacks. The data set is anonymized and the true names of the features provided are hidden.

In the Data tab you will find 3 files: traindata.csv, testdata.csv and sampleSubmission.csv.

Use the training data (traindata.csv) to build your model. Then obtain the predictions for the test set examples (provided in file testdata.csv). To submit your solution you will have to upload a file with header and 2 columns: ID and Class. The file sampleSubmission.csv is an example of a submission file.
