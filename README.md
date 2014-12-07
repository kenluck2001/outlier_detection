Outlier detection in Javascript for stationary data
====================================================

This is the implementation of a multivariate normal distribution model for
predicting the outliers in the data set. There are two kinds of data which are either outliers or normal. The normal data are assumed to have been generated a gaussian distribution. We select a threshold is means truncated the tail shape. This algorithm is symmetry so it can account for both extremes of outliers (high and low). The value of the threshold can be estimated by training performing crossvalidation on a test data set.

This library was built using the syvester.js library. The html files in the bundle show how it should be used in practice.

There is a streaming version of the same algorithm by the same author on https://github.com/kenluck2001/streaming_outlier_detection.
