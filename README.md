# Predicting A Pulsar Star Using SVM and Naive Bayes

## Libraries used:
    Numpy
    Pandas
    Matplotlib
    Seaborn
    Sklearn
    
## Environment:
Google Colab

## Attribute Information:

Each candidate is described by 8 continuous variables, and a single class variable. The first four are simple statistics obtained from the integrated pulse profile (folded profile). This is an array of continuous variables that describe a longitude-resolved version of the signal that has been averaged in both time and frequency . The remaining four variables are similarly obtained from the DM-SNR curve . These are summarised below:

    Mean of the integrated profile.
    Standard deviation of the integrated profile.
    Excess kurtosis of the integrated profile.
    Skewness of the integrated profile.
    Mean of the DM-SNR curve.
    Standard deviation of the DM-SNR curve.
    Excess kurtosis of the DM-SNR curve.
    Skewness of the DM-SNR curve.
    Class

HTRU 2 Summary
17,898 total examples.
1,639 positive examples.
16,259 negative examples.

Source: https://archive.ics.uci.edu/ml/datasets/HTRU2

#### Here SVM and Naive Bayes is used to predict a pulsar star and then a comparison between the accuracy of both the algorithms is done
