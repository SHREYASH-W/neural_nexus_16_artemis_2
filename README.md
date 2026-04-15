**Repo Overview**
The repo consist of two eda's done by paras rawal and priyanshu bhatt before the preprocessing and another one with proper preprocessing and its eda
**Dataset description**
dataset consisted of heterogeneous pediatric medical data  which was structured clinical and demographic features that contained missing values, noise and class imbalance, reflecting real-world healthcare challenges.
dataset consisted 3 csv files, named as train,test and sample_submission
the train.csv had 45 columns and 22,084 rows whereas the test set consist of 43 columns(Genetic disorder and Disorder subclass were removed) and 9,466 rows

**Preprocessing:**
1. column drop that were not significant to achieve the purpose of our problem statement
2. All the NaN/NULL values were replaced by the mean value in the age column(Patient, Mother and Father)
3. All the remaining NaN/NULL values where dropped.
4. Label encoding was done in the processed data.

**What was found in EDA**
EDA was done in 3 notebooks in total, two of them consisted eda without preprocessing and 1 with preprocessing
