# Code for Kaggle Competition for BMI 551 (Statistical Methods)

## Task

The task is to predict whether a breast cancer cell line will respond to treatment with a given drug using the subtype of the tumor and the gene expression data provided.

* There are 25 cell lines and 12 drugs in the training set
* The response are coded as 0 = cell line doesn't respond to drug, or 1 = cell line does respond to drug
* Submissions can be binary or contain values between 0 and 1 so that the area under the ROC curve can be computed for different threshold cutoffs between 0 and 1.
* Once you have a prediction method you will submit predictions for an additional 14 cell lines when treated with the same 12 drugs.
* Your score on 9 of the 14 cell lines will be automatically calculated and displayed.
* Must use two submission techniques, one of which must use (boosting or bagging).
* Work should be done in R.
* A write-up of your method and experimental results is also due at the end of the competition
* Response in this context means that the concentration of drug needed to inhibit cell growth by 50% was above the median for all cell lines tested.

## Provided Data

* **expression.txt** Tab-delimited text file containing expression values for 18,632 genes in 39 samples/cell-lines
* **subtypes.txt** A tab-delimited text file showing the subtypes (basal, luminal, claudin-low and normal-like) for each of the 39 cell lines
* **training_set_answers.txt** Tab-delimited text file showing the correct classification of 0 (non-responsive) or 1 (responsive) for each combination of 25 cell lines and 12 drugs.
* **scoring_and_test_set_id_mappings.csv** A comma-separated file showing the id mappings used by Kaggle for each of the 168 (14x12) cell line/drug combinations in the scoring and test set.  The first 108 values are the scoring set (9 cell lines and 12 drugs), the last 60 are the final test set (5 cell lines and 12 drugs).  
* **rand_sub_cont.csv** Two example submissions files with random guesses


## Statistical Technique

TODO
