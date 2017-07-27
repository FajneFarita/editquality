# Model tuning report
- Revscoring version: 1.3.15
- Features: editquality.feature_lists.ruwiki.damaging
- Date: 2017-07-27T06:46:42.768972
- Observations: 19639
- Labels: [false, true]
- Scoring: roc_auc
- Folds: 5

# Top scoring configurations
| model                      |   mean(scores) |   std(scores) | params                                                                 |
|:---------------------------|---------------:|--------------:|:-----------------------------------------------------------------------|
| GradientBoostingClassifier |          0.935 |         0.007 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=7 |
| GradientBoostingClassifier |          0.935 |         0.005 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=3  |
| GradientBoostingClassifier |          0.935 |         0.006 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=3  |
| GradientBoostingClassifier |          0.935 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=7 |
| GradientBoostingClassifier |          0.935 |         0.007 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=5 |
| GradientBoostingClassifier |          0.934 |         0.006 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=1  |
| GradientBoostingClassifier |          0.934 |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=5  |
| GradientBoostingClassifier |          0.934 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=1  |
| GradientBoostingClassifier |          0.934 |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=7  |
| GradientBoostingClassifier |          0.934 |         0.005 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=1  |

# Models
## RandomForestClassifier
|   mean(scores) |   std(scores) | params                                                                          |
|---------------:|--------------:|:--------------------------------------------------------------------------------|
|          0.933 |         0.006 | criterion="entropy", n_estimators=640, max_features="log2", min_samples_leaf=5  |
|          0.933 |         0.006 | criterion="entropy", n_estimators=640, max_features="log2", min_samples_leaf=7  |
|          0.933 |         0.006 | criterion="entropy", n_estimators=320, max_features="log2", min_samples_leaf=7  |
|          0.933 |         0.006 | criterion="entropy", n_estimators=640, max_features="log2", min_samples_leaf=3  |
|          0.933 |         0.006 | criterion="entropy", n_estimators=320, max_features="log2", min_samples_leaf=5  |
|          0.933 |         0.006 | criterion="entropy", n_estimators=320, max_features="log2", min_samples_leaf=13 |
|          0.933 |         0.007 | criterion="entropy", n_estimators=160, max_features="log2", min_samples_leaf=5  |
|          0.933 |         0.006 | criterion="entropy", n_estimators=640, max_features="log2", min_samples_leaf=13 |
|          0.932 |         0.006 | criterion="entropy", n_estimators=320, max_features="log2", min_samples_leaf=3  |
|          0.932 |         0.006 | criterion="entropy", n_estimators=160, max_features="log2", min_samples_leaf=7  |
|          0.932 |         0.006 | criterion="entropy", n_estimators=160, max_features="log2", min_samples_leaf=13 |
|          0.932 |         0.006 | criterion="gini", n_estimators=640, max_features="log2", min_samples_leaf=5     |
|          0.932 |         0.006 | criterion="entropy", n_estimators=160, max_features="log2", min_samples_leaf=3  |
|          0.932 |         0.006 | criterion="gini", n_estimators=320, max_features="log2", min_samples_leaf=5     |
|          0.931 |         0.006 | criterion="gini", n_estimators=320, max_features="log2", min_samples_leaf=7     |
|          0.931 |         0.006 | criterion="entropy", n_estimators=80, max_features="log2", min_samples_leaf=5   |
|          0.931 |         0.006 | criterion="gini", n_estimators=640, max_features="log2", min_samples_leaf=7     |
|          0.931 |         0.006 | criterion="gini", n_estimators=640, max_features="log2", min_samples_leaf=3     |
|          0.931 |         0.006 | criterion="entropy", n_estimators=80, max_features="log2", min_samples_leaf=13  |
|          0.931 |         0.006 | criterion="gini", n_estimators=160, max_features="log2", min_samples_leaf=3     |
|          0.931 |         0.006 | criterion="gini", n_estimators=640, max_features="log2", min_samples_leaf=13    |
|          0.931 |         0.007 | criterion="gini", n_estimators=320, max_features="log2", min_samples_leaf=13    |
|          0.931 |         0.006 | criterion="entropy", n_estimators=320, max_features="log2", min_samples_leaf=1  |
|          0.931 |         0.005 | criterion="entropy", n_estimators=640, max_features="log2", min_samples_leaf=1  |
|          0.931 |         0.006 | criterion="gini", n_estimators=160, max_features="log2", min_samples_leaf=7     |
|          0.931 |         0.005 | criterion="entropy", n_estimators=80, max_features="log2", min_samples_leaf=7   |
|          0.931 |         0.007 | criterion="entropy", n_estimators=80, max_features="log2", min_samples_leaf=3   |
|          0.93  |         0.007 | criterion="gini", n_estimators=160, max_features="log2", min_samples_leaf=5     |
|          0.93  |         0.007 | criterion="gini", n_estimators=80, max_features="log2", min_samples_leaf=7      |
|          0.93  |         0.007 | criterion="gini", n_estimators=320, max_features="log2", min_samples_leaf=3     |
|          0.93  |         0.007 | criterion="gini", n_estimators=160, max_features="log2", min_samples_leaf=13    |
|          0.93  |         0.007 | criterion="gini", n_estimators=80, max_features="log2", min_samples_leaf=13     |
|          0.93  |         0.006 | criterion="entropy", n_estimators=40, max_features="log2", min_samples_leaf=13  |
|          0.929 |         0.008 | criterion="gini", n_estimators=80, max_features="log2", min_samples_leaf=5      |
|          0.929 |         0.007 | criterion="entropy", n_estimators=160, max_features="log2", min_samples_leaf=1  |
|          0.929 |         0.007 | criterion="gini", n_estimators=640, max_features="log2", min_samples_leaf=1     |
|          0.929 |         0.008 | criterion="gini", n_estimators=40, max_features="log2", min_samples_leaf=13     |
|          0.928 |         0.006 | criterion="gini", n_estimators=80, max_features="log2", min_samples_leaf=3      |
|          0.928 |         0.005 | criterion="gini", n_estimators=320, max_features="log2", min_samples_leaf=1     |
|          0.928 |         0.007 | criterion="entropy", n_estimators=40, max_features="log2", min_samples_leaf=7   |
|          0.927 |         0.005 | criterion="entropy", n_estimators=40, max_features="log2", min_samples_leaf=5   |
|          0.927 |         0.007 | criterion="entropy", n_estimators=20, max_features="log2", min_samples_leaf=13  |
|          0.927 |         0.007 | criterion="gini", n_estimators=40, max_features="log2", min_samples_leaf=7      |
|          0.927 |         0.005 | criterion="gini", n_estimators=40, max_features="log2", min_samples_leaf=5      |
|          0.927 |         0.007 | criterion="gini", n_estimators=160, max_features="log2", min_samples_leaf=1     |
|          0.926 |         0.005 | criterion="gini", n_estimators=40, max_features="log2", min_samples_leaf=3      |
|          0.926 |         0.008 | criterion="entropy", n_estimators=80, max_features="log2", min_samples_leaf=1   |
|          0.925 |         0.009 | criterion="entropy", n_estimators=40, max_features="log2", min_samples_leaf=3   |
|          0.925 |         0.008 | criterion="entropy", n_estimators=20, max_features="log2", min_samples_leaf=7   |
|          0.924 |         0.006 | criterion="entropy", n_estimators=20, max_features="log2", min_samples_leaf=3   |
|          0.924 |         0.009 | criterion="gini", n_estimators=20, max_features="log2", min_samples_leaf=13     |
|          0.923 |         0.004 | criterion="entropy", n_estimators=20, max_features="log2", min_samples_leaf=5   |
|          0.923 |         0.006 | criterion="gini", n_estimators=20, max_features="log2", min_samples_leaf=7      |
|          0.923 |         0.006 | criterion="gini", n_estimators=80, max_features="log2", min_samples_leaf=1      |
|          0.921 |         0.006 | criterion="gini", n_estimators=20, max_features="log2", min_samples_leaf=3      |
|          0.921 |         0.009 | criterion="entropy", n_estimators=10, max_features="log2", min_samples_leaf=13  |
|          0.921 |         0.009 | criterion="gini", n_estimators=20, max_features="log2", min_samples_leaf=5      |
|          0.917 |         0.012 | criterion="entropy", n_estimators=10, max_features="log2", min_samples_leaf=7   |
|          0.916 |         0.011 | criterion="gini", n_estimators=40, max_features="log2", min_samples_leaf=1      |
|          0.916 |         0.015 | criterion="gini", n_estimators=10, max_features="log2", min_samples_leaf=13     |
|          0.916 |         0.007 | criterion="gini", n_estimators=10, max_features="log2", min_samples_leaf=7      |
|          0.915 |         0.01  | criterion="entropy", n_estimators=40, max_features="log2", min_samples_leaf=1   |
|          0.914 |         0.009 | criterion="entropy", n_estimators=10, max_features="log2", min_samples_leaf=5   |
|          0.909 |         0.008 | criterion="gini", n_estimators=10, max_features="log2", min_samples_leaf=5      |
|          0.904 |         0.015 | criterion="entropy", n_estimators=10, max_features="log2", min_samples_leaf=3   |
|          0.903 |         0.007 | criterion="entropy", n_estimators=20, max_features="log2", min_samples_leaf=1   |
|          0.899 |         0.01  | criterion="gini", n_estimators=10, max_features="log2", min_samples_leaf=3      |
|          0.895 |         0.015 | criterion="gini", n_estimators=20, max_features="log2", min_samples_leaf=1      |
|          0.864 |         0.007 | criterion="entropy", n_estimators=10, max_features="log2", min_samples_leaf=1   |
|          0.857 |         0.011 | criterion="gini", n_estimators=10, max_features="log2", min_samples_leaf=1      |

## GradientBoostingClassifier
|   mean(scores) |   std(scores) | params                                                                 |
|---------------:|--------------:|:-----------------------------------------------------------------------|
|          0.935 |         0.007 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.935 |         0.005 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.935 |         0.006 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.935 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.935 |         0.007 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.934 |         0.006 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.934 |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.934 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.934 |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.934 |         0.005 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.934 |         0.007 | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.934 |         0.004 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.934 |         0.006 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.933 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.933 |         0.005 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.932 |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.932 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.931 |         0.007 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.931 |         0.007 | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.931 |         0.007 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.93  |         0.004 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.93  |         0.006 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.93  |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.93  |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.929 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.929 |         0.006 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.928 |         0.007 | n_estimators=100, max_features="log2", learning_rate=1, max_depth=1    |
|          0.928 |         0.005 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.928 |         0.005 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.927 |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.926 |         0.01  | n_estimators=300, max_features="log2", learning_rate=1, max_depth=1    |
|          0.926 |         0.007 | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.925 |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.924 |         0.01  | n_estimators=500, max_features="log2", learning_rate=1, max_depth=1    |
|          0.923 |         0.005 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.921 |         0.005 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.92  |         0.005 | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.919 |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.918 |         0.014 | n_estimators=700, max_features="log2", learning_rate=1, max_depth=1    |
|          0.916 |         0.011 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.916 |         0.004 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.915 |         0.007 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.915 |         0.006 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.915 |         0.002 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.914 |         0.004 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.913 |         0.007 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.912 |         0.005 | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.91  |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.91  |         0.011 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.907 |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.9   |         0.043 | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.893 |         0.039 | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.892 |         0.018 | n_estimators=500, max_features="log2", learning_rate=1, max_depth=3    |
|          0.891 |         0.022 | n_estimators=100, max_features="log2", learning_rate=1, max_depth=3    |
|          0.886 |         0.024 | n_estimators=300, max_features="log2", learning_rate=1, max_depth=3    |
|          0.855 |         0.015 | n_estimators=100, max_features="log2", learning_rate=1, max_depth=5    |
|          0.843 |         0.031 | n_estimators=100, max_features="log2", learning_rate=1, max_depth=7    |
|          0.829 |         0.043 | n_estimators=300, max_features="log2", learning_rate=1, max_depth=5    |
|          0.804 |         0.028 | n_estimators=500, max_features="log2", learning_rate=1, max_depth=5    |
|          0.769 |         0.132 | n_estimators=700, max_features="log2", learning_rate=1, max_depth=3    |
|          0.723 |         0.064 | n_estimators=700, max_features="log2", learning_rate=1, max_depth=5    |
|          0.721 |         0.157 | n_estimators=500, max_features="log2", learning_rate=1, max_depth=7    |
|          0.721 |         0.071 | n_estimators=300, max_features="log2", learning_rate=1, max_depth=7    |
|          0     |         0     | n_estimators=700, max_features="log2", learning_rate=1, max_depth=7    |

## BernoulliNB
|   mean(scores) |   std(scores) | params   |
|---------------:|--------------:|:---------|
|          0.875 |         0.009 |          |

## LogisticRegression
|   mean(scores) |   std(scores) | params              |
|---------------:|--------------:|:--------------------|
|          0.925 |         0.007 | penalty="l1", C=1   |
|          0.925 |         0.007 | penalty="l1", C=10  |
|          0.923 |         0.006 | penalty="l1", C=0.1 |
|          0.896 |         0.011 | penalty="l2", C=10  |
|          0.895 |         0.005 | penalty="l2", C=0.1 |
|          0.894 |         0.011 | penalty="l2", C=1   |

## GaussianNB
|   mean(scores) |   std(scores) | params   |
|---------------:|--------------:|:---------|
|          0.893 |         0.014 |          |

