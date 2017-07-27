# Model tuning report
- Revscoring version: 1.3.15
- Features: editquality.feature_lists.ruwiki.goodfaith
- Date: 2017-07-27T07:07:24.464851
- Observations: 19639
- Labels: [false, true]
- Scoring: roc_auc
- Folds: 5

# Top scoring configurations
| model                      |   mean(scores) |   std(scores) | params                                                                          |
|:---------------------------|---------------:|--------------:|:--------------------------------------------------------------------------------|
| GradientBoostingClassifier |          0.936 |         0.008 | n_estimators=700, max_depth=7, learning_rate=0.01, max_features="log2"          |
| RandomForestClassifier     |          0.935 |         0.005 | min_samples_leaf=5, criterion="entropy", n_estimators=640, max_features="log2"  |
| RandomForestClassifier     |          0.934 |         0.005 | min_samples_leaf=3, criterion="entropy", n_estimators=640, max_features="log2"  |
| RandomForestClassifier     |          0.934 |         0.005 | min_samples_leaf=7, criterion="entropy", n_estimators=320, max_features="log2"  |
| GradientBoostingClassifier |          0.934 |         0.007 | n_estimators=500, max_depth=7, learning_rate=0.01, max_features="log2"          |
| RandomForestClassifier     |          0.934 |         0.005 | min_samples_leaf=7, criterion="entropy", n_estimators=640, max_features="log2"  |
| RandomForestClassifier     |          0.934 |         0.006 | min_samples_leaf=5, criterion="entropy", n_estimators=320, max_features="log2"  |
| GradientBoostingClassifier |          0.934 |         0.006 | n_estimators=700, max_depth=5, learning_rate=0.01, max_features="log2"          |
| RandomForestClassifier     |          0.934 |         0.006 | min_samples_leaf=13, criterion="entropy", n_estimators=640, max_features="log2" |
| GradientBoostingClassifier |          0.934 |         0.007 | n_estimators=500, max_depth=5, learning_rate=0.01, max_features="log2"          |

# Models
## BernoulliNB
|   mean(scores) |   std(scores) | params   |
|---------------:|--------------:|:---------|
|          0.868 |         0.018 |          |

## GradientBoostingClassifier
|   mean(scores) |   std(scores) | params                                                                 |
|---------------:|--------------:|:-----------------------------------------------------------------------|
|          0.936 |         0.008 | n_estimators=700, max_depth=7, learning_rate=0.01, max_features="log2" |
|          0.934 |         0.007 | n_estimators=500, max_depth=7, learning_rate=0.01, max_features="log2" |
|          0.934 |         0.006 | n_estimators=700, max_depth=5, learning_rate=0.01, max_features="log2" |
|          0.934 |         0.007 | n_estimators=500, max_depth=5, learning_rate=0.01, max_features="log2" |
|          0.933 |         0.007 | n_estimators=300, max_depth=7, learning_rate=0.01, max_features="log2" |
|          0.933 |         0.007 | n_estimators=300, max_depth=3, learning_rate=0.1, max_features="log2"  |
|          0.932 |         0.007 | n_estimators=300, max_depth=5, learning_rate=0.01, max_features="log2" |
|          0.931 |         0.006 | n_estimators=100, max_depth=7, learning_rate=0.01, max_features="log2" |
|          0.931 |         0.007 | n_estimators=500, max_depth=3, learning_rate=0.1, max_features="log2"  |
|          0.931 |         0.007 | n_estimators=700, max_depth=3, learning_rate=0.01, max_features="log2" |
|          0.931 |         0.008 | n_estimators=100, max_depth=3, learning_rate=0.1, max_features="log2"  |
|          0.93  |         0.009 | n_estimators=300, max_depth=5, learning_rate=0.1, max_features="log2"  |
|          0.93  |         0.01  | n_estimators=700, max_depth=3, learning_rate=0.1, max_features="log2"  |
|          0.93  |         0.005 | n_estimators=700, max_depth=1, learning_rate=0.1, max_features="log2"  |
|          0.93  |         0.008 | n_estimators=100, max_depth=5, learning_rate=0.1, max_features="log2"  |
|          0.93  |         0.007 | n_estimators=300, max_depth=1, learning_rate=0.5, max_features="log2"  |
|          0.929 |         0.007 | n_estimators=500, max_depth=3, learning_rate=0.01, max_features="log2" |
|          0.929 |         0.007 | n_estimators=100, max_depth=7, learning_rate=0.1, max_features="log2"  |
|          0.929 |         0.006 | n_estimators=500, max_depth=1, learning_rate=0.5, max_features="log2"  |
|          0.929 |         0.007 | n_estimators=700, max_depth=7, learning_rate=0.1, max_features="log2"  |
|          0.929 |         0.009 | n_estimators=700, max_depth=5, learning_rate=0.1, max_features="log2"  |
|          0.928 |         0.007 | n_estimators=500, max_depth=7, learning_rate=0.1, max_features="log2"  |
|          0.928 |         0.007 | n_estimators=500, max_depth=5, learning_rate=0.1, max_features="log2"  |
|          0.928 |         0.006 | n_estimators=500, max_depth=1, learning_rate=0.1, max_features="log2"  |
|          0.928 |         0.007 | n_estimators=100, max_depth=5, learning_rate=0.01, max_features="log2" |
|          0.927 |         0.004 | n_estimators=300, max_depth=1, learning_rate=0.1, max_features="log2"  |
|          0.927 |         0.006 | n_estimators=300, max_depth=3, learning_rate=0.01, max_features="log2" |
|          0.927 |         0.007 | n_estimators=300, max_depth=7, learning_rate=0.1, max_features="log2"  |
|          0.925 |         0.011 | n_estimators=700, max_depth=1, learning_rate=0.5, max_features="log2"  |
|          0.924 |         0.006 | n_estimators=100, max_depth=1, learning_rate=0.5, max_features="log2"  |
|          0.924 |         0.004 | n_estimators=100, max_depth=1, learning_rate=0.1, max_features="log2"  |
|          0.922 |         0.004 | n_estimators=700, max_depth=1, learning_rate=0.01, max_features="log2" |
|          0.922 |         0.005 | n_estimators=100, max_depth=3, learning_rate=0.01, max_features="log2" |
|          0.919 |         0.005 | n_estimators=500, max_depth=1, learning_rate=0.01, max_features="log2" |
|          0.916 |         0.013 | n_estimators=300, max_depth=1, learning_rate=1, max_features="log2"    |
|          0.916 |         0.015 | n_estimators=700, max_depth=1, learning_rate=1, max_features="log2"    |
|          0.913 |         0.013 | n_estimators=100, max_depth=3, learning_rate=0.5, max_features="log2"  |
|          0.913 |         0.004 | n_estimators=300, max_depth=1, learning_rate=0.01, max_features="log2" |
|          0.907 |         0.004 | n_estimators=100, max_depth=1, learning_rate=0.01, max_features="log2" |
|          0.906 |         0.013 | n_estimators=700, max_depth=3, learning_rate=0.5, max_features="log2"  |
|          0.906 |         0.01  | n_estimators=500, max_depth=3, learning_rate=0.5, max_features="log2"  |
|          0.905 |         0.014 | n_estimators=300, max_depth=5, learning_rate=0.5, max_features="log2"  |
|          0.905 |         0.007 | n_estimators=500, max_depth=7, learning_rate=0.5, max_features="log2"  |
|          0.899 |         0.017 | n_estimators=700, max_depth=7, learning_rate=0.5, max_features="log2"  |
|          0.898 |         0.038 | n_estimators=100, max_depth=1, learning_rate=1, max_features="log2"    |
|          0.897 |         0.019 | n_estimators=100, max_depth=5, learning_rate=0.5, max_features="log2"  |
|          0.895 |         0.017 | n_estimators=300, max_depth=3, learning_rate=0.5, max_features="log2"  |
|          0.894 |         0.011 | n_estimators=100, max_depth=7, learning_rate=0.5, max_features="log2"  |
|          0.891 |         0.024 | n_estimators=700, max_depth=5, learning_rate=0.5, max_features="log2"  |
|          0.89  |         0.036 | n_estimators=500, max_depth=1, learning_rate=1, max_features="log2"    |
|          0.885 |         0.05  | n_estimators=500, max_depth=5, learning_rate=0.5, max_features="log2"  |
|          0.864 |         0.018 | n_estimators=100, max_depth=3, learning_rate=1, max_features="log2"    |
|          0.826 |         0.058 | n_estimators=300, max_depth=3, learning_rate=1, max_features="log2"    |
|          0.803 |         0.018 | n_estimators=700, max_depth=3, learning_rate=1, max_features="log2"    |
|          0.799 |         0.035 | n_estimators=500, max_depth=3, learning_rate=1, max_features="log2"    |
|          0.79  |         0.041 | n_estimators=500, max_depth=5, learning_rate=1, max_features="log2"    |
|          0.787 |         0.057 | n_estimators=100, max_depth=5, learning_rate=1, max_features="log2"    |
|          0.696 |         0.103 | n_estimators=300, max_depth=5, learning_rate=1, max_features="log2"    |
|          0.672 |         0.077 | n_estimators=700, max_depth=7, learning_rate=1, max_features="log2"    |
|          0.653 |         0.171 | n_estimators=300, max_depth=7, learning_rate=1, max_features="log2"    |
|          0.636 |         0.117 | n_estimators=500, max_depth=7, learning_rate=1, max_features="log2"    |
|          0     |         0     | n_estimators=300, max_depth=7, learning_rate=0.5, max_features="log2"  |
|          0     |         0     | n_estimators=700, max_depth=5, learning_rate=1, max_features="log2"    |
|          0     |         0     | n_estimators=100, max_depth=7, learning_rate=1, max_features="log2"    |

## GaussianNB
|   mean(scores) |   std(scores) | params   |
|---------------:|--------------:|:---------|
|          0.893 |         0.009 |          |

## RandomForestClassifier
|   mean(scores) |   std(scores) | params                                                                          |
|---------------:|--------------:|:--------------------------------------------------------------------------------|
|          0.935 |         0.005 | min_samples_leaf=5, criterion="entropy", n_estimators=640, max_features="log2"  |
|          0.934 |         0.005 | min_samples_leaf=3, criterion="entropy", n_estimators=640, max_features="log2"  |
|          0.934 |         0.005 | min_samples_leaf=7, criterion="entropy", n_estimators=320, max_features="log2"  |
|          0.934 |         0.005 | min_samples_leaf=7, criterion="entropy", n_estimators=640, max_features="log2"  |
|          0.934 |         0.006 | min_samples_leaf=5, criterion="entropy", n_estimators=320, max_features="log2"  |
|          0.934 |         0.006 | min_samples_leaf=13, criterion="entropy", n_estimators=640, max_features="log2" |
|          0.934 |         0.005 | min_samples_leaf=5, criterion="entropy", n_estimators=80, max_features="log2"   |
|          0.933 |         0.005 | min_samples_leaf=13, criterion="entropy", n_estimators=80, max_features="log2"  |
|          0.933 |         0.005 | min_samples_leaf=7, criterion="entropy", n_estimators=160, max_features="log2"  |
|          0.933 |         0.004 | min_samples_leaf=1, criterion="entropy", n_estimators=640, max_features="log2"  |
|          0.933 |         0.005 | min_samples_leaf=13, criterion="entropy", n_estimators=160, max_features="log2" |
|          0.933 |         0.006 | min_samples_leaf=13, criterion="gini", n_estimators=160, max_features="log2"    |
|          0.933 |         0.006 | min_samples_leaf=13, criterion="entropy", n_estimators=320, max_features="log2" |
|          0.933 |         0.005 | min_samples_leaf=3, criterion="entropy", n_estimators=320, max_features="log2"  |
|          0.932 |         0.005 | min_samples_leaf=7, criterion="gini", n_estimators=640, max_features="log2"     |
|          0.932 |         0.006 | min_samples_leaf=5, criterion="gini", n_estimators=160, max_features="log2"     |
|          0.932 |         0.006 | min_samples_leaf=5, criterion="gini", n_estimators=640, max_features="log2"     |
|          0.932 |         0.006 | min_samples_leaf=5, criterion="gini", n_estimators=320, max_features="log2"     |
|          0.932 |         0.003 | min_samples_leaf=5, criterion="entropy", n_estimators=160, max_features="log2"  |
|          0.932 |         0.007 | min_samples_leaf=13, criterion="gini", n_estimators=640, max_features="log2"    |
|          0.931 |         0.006 | min_samples_leaf=7, criterion="gini", n_estimators=320, max_features="log2"     |
|          0.931 |         0.006 | min_samples_leaf=3, criterion="gini", n_estimators=640, max_features="log2"     |
|          0.931 |         0.006 | min_samples_leaf=13, criterion="gini", n_estimators=320, max_features="log2"    |
|          0.931 |         0.005 | min_samples_leaf=1, criterion="entropy", n_estimators=320, max_features="log2"  |
|          0.93  |         0.005 | min_samples_leaf=3, criterion="gini", n_estimators=320, max_features="log2"     |
|          0.93  |         0.006 | min_samples_leaf=7, criterion="gini", n_estimators=160, max_features="log2"     |
|          0.93  |         0.007 | min_samples_leaf=7, criterion="gini", n_estimators=80, max_features="log2"      |
|          0.93  |         0.003 | min_samples_leaf=3, criterion="entropy", n_estimators=160, max_features="log2"  |
|          0.93  |         0.006 | min_samples_leaf=3, criterion="entropy", n_estimators=80, max_features="log2"   |
|          0.93  |         0.007 | min_samples_leaf=13, criterion="gini", n_estimators=80, max_features="log2"     |
|          0.929 |         0.007 | min_samples_leaf=3, criterion="gini", n_estimators=160, max_features="log2"     |
|          0.929 |         0.005 | min_samples_leaf=5, criterion="entropy", n_estimators=40, max_features="log2"   |
|          0.929 |         0.006 | min_samples_leaf=5, criterion="gini", n_estimators=80, max_features="log2"      |
|          0.929 |         0.007 | min_samples_leaf=7, criterion="entropy", n_estimators=80, max_features="log2"   |
|          0.929 |         0.003 | min_samples_leaf=5, criterion="gini", n_estimators=40, max_features="log2"      |
|          0.929 |         0.005 | min_samples_leaf=1, criterion="gini", n_estimators=320, max_features="log2"     |
|          0.928 |         0.005 | min_samples_leaf=1, criterion="gini", n_estimators=640, max_features="log2"     |
|          0.928 |         0.009 | min_samples_leaf=1, criterion="entropy", n_estimators=160, max_features="log2"  |
|          0.928 |         0.006 | min_samples_leaf=13, criterion="entropy", n_estimators=40, max_features="log2"  |
|          0.928 |         0.007 | min_samples_leaf=13, criterion="gini", n_estimators=40, max_features="log2"     |
|          0.928 |         0.007 | min_samples_leaf=7, criterion="entropy", n_estimators=40, max_features="log2"   |
|          0.926 |         0.008 | min_samples_leaf=7, criterion="gini", n_estimators=40, max_features="log2"      |
|          0.925 |         0.009 | min_samples_leaf=13, criterion="entropy", n_estimators=20, max_features="log2"  |
|          0.924 |         0.009 | min_samples_leaf=3, criterion="gini", n_estimators=80, max_features="log2"      |
|          0.923 |         0.007 | min_samples_leaf=1, criterion="gini", n_estimators=160, max_features="log2"     |
|          0.923 |         0.007 | min_samples_leaf=7, criterion="entropy", n_estimators=20, max_features="log2"   |
|          0.923 |         0.006 | min_samples_leaf=13, criterion="gini", n_estimators=20, max_features="log2"     |
|          0.922 |         0.007 | min_samples_leaf=3, criterion="entropy", n_estimators=40, max_features="log2"   |
|          0.922 |         0.006 | min_samples_leaf=3, criterion="gini", n_estimators=40, max_features="log2"      |
|          0.921 |         0.008 | min_samples_leaf=7, criterion="gini", n_estimators=20, max_features="log2"      |
|          0.92  |         0.009 | min_samples_leaf=5, criterion="gini", n_estimators=20, max_features="log2"      |
|          0.919 |         0.01  | min_samples_leaf=5, criterion="entropy", n_estimators=20, max_features="log2"   |
|          0.919 |         0.006 | min_samples_leaf=13, criterion="entropy", n_estimators=10, max_features="log2"  |
|          0.917 |         0.006 | min_samples_leaf=1, criterion="gini", n_estimators=80, max_features="log2"      |
|          0.916 |         0.008 | min_samples_leaf=13, criterion="gini", n_estimators=10, max_features="log2"     |
|          0.916 |         0.004 | min_samples_leaf=1, criterion="entropy", n_estimators=80, max_features="log2"   |
|          0.911 |         0.009 | min_samples_leaf=3, criterion="entropy", n_estimators=20, max_features="log2"   |
|          0.909 |         0.012 | min_samples_leaf=3, criterion="gini", n_estimators=20, max_features="log2"      |
|          0.908 |         0.007 | min_samples_leaf=1, criterion="entropy", n_estimators=40, max_features="log2"   |
|          0.906 |         0.009 | min_samples_leaf=7, criterion="gini", n_estimators=10, max_features="log2"      |
|          0.905 |         0.016 | min_samples_leaf=7, criterion="entropy", n_estimators=10, max_features="log2"   |
|          0.904 |         0.012 | min_samples_leaf=5, criterion="gini", n_estimators=10, max_features="log2"      |
|          0.904 |         0.006 | min_samples_leaf=1, criterion="gini", n_estimators=40, max_features="log2"      |
|          0.904 |         0.01  | min_samples_leaf=5, criterion="entropy", n_estimators=10, max_features="log2"   |
|          0.885 |         0.02  | min_samples_leaf=3, criterion="gini", n_estimators=10, max_features="log2"      |
|          0.884 |         0.013 | min_samples_leaf=3, criterion="entropy", n_estimators=10, max_features="log2"   |
|          0.882 |         0.011 | min_samples_leaf=1, criterion="gini", n_estimators=20, max_features="log2"      |
|          0.872 |         0.01  | min_samples_leaf=1, criterion="entropy", n_estimators=20, max_features="log2"   |
|          0.811 |         0.019 | min_samples_leaf=1, criterion="entropy", n_estimators=10, max_features="log2"   |
|          0.81  |         0.023 | min_samples_leaf=1, criterion="gini", n_estimators=10, max_features="log2"      |

## LogisticRegression
|   mean(scores) |   std(scores) | params              |
|---------------:|--------------:|:--------------------|
|          0.917 |         0.01  | C=1, penalty="l1"   |
|          0.916 |         0.01  | C=0.1, penalty="l1" |
|          0.914 |         0.01  | C=10, penalty="l1"  |
|          0.886 |         0.011 | C=10, penalty="l2"  |
|          0.882 |         0.011 | C=1, penalty="l2"   |
|          0.881 |         0.009 | C=0.1, penalty="l2" |

