# Model tuning report
- Revscoring version: 1.3.15
- Features: editquality.feature_lists.ruwiki.reverted
- Date: 2017-07-27T06:25:00.865063
- Observations: 19639
- Labels: [false, true]
- Scoring: roc_auc
- Folds: 5

# Top scoring configurations
| model                      |   mean(scores) |   std(scores) | params                                                                         |
|:---------------------------|---------------:|--------------:|:-------------------------------------------------------------------------------|
| GradientBoostingClassifier |          0.891 |         0.008 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=7         |
| GradientBoostingClassifier |          0.891 |         0.008 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=7         |
| RandomForestClassifier     |          0.891 |         0.01  | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=3 |
| RandomForestClassifier     |          0.891 |         0.009 | n_estimators=320, max_features="log2", criterion="entropy", min_samples_leaf=7 |
| RandomForestClassifier     |          0.89  |         0.01  | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=5 |
| RandomForestClassifier     |          0.89  |         0.01  | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=7 |
| GradientBoostingClassifier |          0.89  |         0.009 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=5         |
| RandomForestClassifier     |          0.89  |         0.009 | n_estimators=320, max_features="log2", criterion="entropy", min_samples_leaf=5 |
| GradientBoostingClassifier |          0.89  |         0.008 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=5         |
| RandomForestClassifier     |          0.889 |         0.01  | n_estimators=160, max_features="log2", criterion="entropy", min_samples_leaf=7 |

# Models
## BernoulliNB
|   mean(scores) |   std(scores) | params   |
|---------------:|--------------:|:---------|
|          0.805 |         0.013 |          |

## GradientBoostingClassifier
|   mean(scores) |   std(scores) | params                                                                 |
|---------------:|--------------:|:-----------------------------------------------------------------------|
|          0.891 |         0.008 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.891 |         0.008 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.89  |         0.009 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.89  |         0.008 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.888 |         0.008 | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.887 |         0.008 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.885 |         0.01  | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.885 |         0.01  | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.884 |         0.009 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.884 |         0.008 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.883 |         0.009 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.883 |         0.01  | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.882 |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.882 |         0.009 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.881 |         0.011 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=7 |
|          0.881 |         0.01  | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.88  |         0.01  | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.88  |         0.011 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.88  |         0.009 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.879 |         0.011 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=3  |
|          0.879 |         0.009 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.879 |         0.009 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=1  |
|          0.878 |         0.012 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.876 |         0.006 | n_estimators=300, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.876 |         0.006 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.875 |         0.009 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=5 |
|          0.875 |         0.008 | n_estimators=500, max_features="log2", learning_rate=1, max_depth=1    |
|          0.874 |         0.007 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.874 |         0.01  | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.874 |         0.008 | n_estimators=300, max_features="log2", learning_rate=1, max_depth=1    |
|          0.874 |         0.006 | n_estimators=500, max_features="log2", learning_rate=0.1, max_depth=5  |
|          0.873 |         0.003 | n_estimators=700, max_features="log2", learning_rate=0.1, max_depth=7  |
|          0.873 |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.871 |         0.01  | n_estimators=700, max_features="log2", learning_rate=1, max_depth=1    |
|          0.869 |         0.011 | n_estimators=100, max_features="log2", learning_rate=0.1, max_depth=1  |
|          0.867 |         0.009 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=3 |
|          0.867 |         0.004 | n_estimators=100, max_features="log2", learning_rate=1, max_depth=1    |
|          0.866 |         0.009 | n_estimators=700, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.863 |         0.008 | n_estimators=500, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.86  |         0.009 | n_estimators=300, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.854 |         0.009 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.854 |         0.008 | n_estimators=100, max_features="log2", learning_rate=0.01, max_depth=1 |
|          0.85  |         0.006 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.85  |         0.007 | n_estimators=100, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.85  |         0.006 | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.849 |         0.015 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.848 |         0.009 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.848 |         0.008 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.845 |         0.003 | n_estimators=700, max_features="log2", learning_rate=0.5, max_depth=3  |
|          0.845 |         0.015 | n_estimators=300, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.844 |         0.012 | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=5  |
|          0.844 |         0.011 | n_estimators=100, max_features="log2", learning_rate=1, max_depth=3    |
|          0.84  |         0.006 | n_estimators=500, max_features="log2", learning_rate=0.5, max_depth=7  |
|          0.787 |         0.053 | n_estimators=300, max_features="log2", learning_rate=1, max_depth=3    |
|          0.78  |         0.042 | n_estimators=700, max_features="log2", learning_rate=1, max_depth=3    |
|          0.78  |         0.03  | n_estimators=100, max_features="log2", learning_rate=1, max_depth=5    |
|          0.764 |         0.016 | n_estimators=100, max_features="log2", learning_rate=1, max_depth=7    |
|          0.749 |         0.06  | n_estimators=500, max_features="log2", learning_rate=1, max_depth=3    |
|          0.713 |         0.036 | n_estimators=300, max_features="log2", learning_rate=1, max_depth=5    |
|          0.693 |         0.099 | n_estimators=700, max_features="log2", learning_rate=1, max_depth=5    |
|          0.668 |         0.083 | n_estimators=300, max_features="log2", learning_rate=1, max_depth=7    |
|          0.58  |         0.083 | n_estimators=500, max_features="log2", learning_rate=1, max_depth=7    |
|          0.517 |         0.139 | n_estimators=700, max_features="log2", learning_rate=1, max_depth=7    |
|          0     |         0     | n_estimators=500, max_features="log2", learning_rate=1, max_depth=5    |

## RandomForestClassifier
|   mean(scores) |   std(scores) | params                                                                          |
|---------------:|--------------:|:--------------------------------------------------------------------------------|
|          0.891 |         0.01  | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=3  |
|          0.891 |         0.009 | n_estimators=320, max_features="log2", criterion="entropy", min_samples_leaf=7  |
|          0.89  |         0.01  | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=5  |
|          0.89  |         0.01  | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=7  |
|          0.89  |         0.009 | n_estimators=320, max_features="log2", criterion="entropy", min_samples_leaf=5  |
|          0.889 |         0.01  | n_estimators=160, max_features="log2", criterion="entropy", min_samples_leaf=7  |
|          0.889 |         0.009 | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=13 |
|          0.889 |         0.01  | n_estimators=320, max_features="log2", criterion="entropy", min_samples_leaf=3  |
|          0.889 |         0.009 | n_estimators=640, max_features="log2", criterion="entropy", min_samples_leaf=1  |
|          0.888 |         0.009 | n_estimators=320, max_features="log2", criterion="entropy", min_samples_leaf=13 |
|          0.888 |         0.011 | n_estimators=160, max_features="log2", criterion="entropy", min_samples_leaf=5  |
|          0.888 |         0.009 | n_estimators=640, max_features="log2", criterion="gini", min_samples_leaf=7     |
|          0.887 |         0.008 | n_estimators=80, max_features="log2", criterion="entropy", min_samples_leaf=13  |
|          0.887 |         0.009 | n_estimators=160, max_features="log2", criterion="entropy", min_samples_leaf=13 |
|          0.887 |         0.009 | n_estimators=160, max_features="log2", criterion="entropy", min_samples_leaf=3  |
|          0.887 |         0.009 | n_estimators=160, max_features="log2", criterion="gini", min_samples_leaf=5     |
|          0.887 |         0.01  | n_estimators=80, max_features="log2", criterion="entropy", min_samples_leaf=5   |
|          0.886 |         0.01  | n_estimators=40, max_features="log2", criterion="entropy", min_samples_leaf=7   |
|          0.886 |         0.01  | n_estimators=80, max_features="log2", criterion="entropy", min_samples_leaf=7   |
|          0.886 |         0.01  | n_estimators=640, max_features="log2", criterion="gini", min_samples_leaf=5     |
|          0.886 |         0.011 | n_estimators=320, max_features="log2", criterion="entropy", min_samples_leaf=1  |
|          0.886 |         0.01  | n_estimators=160, max_features="log2", criterion="gini", min_samples_leaf=13    |
|          0.886 |         0.01  | n_estimators=640, max_features="log2", criterion="gini", min_samples_leaf=13    |
|          0.886 |         0.01  | n_estimators=320, max_features="log2", criterion="gini", min_samples_leaf=13    |
|          0.885 |         0.01  | n_estimators=640, max_features="log2", criterion="gini", min_samples_leaf=3     |
|          0.885 |         0.01  | n_estimators=160, max_features="log2", criterion="gini", min_samples_leaf=7     |
|          0.885 |         0.01  | n_estimators=320, max_features="log2", criterion="gini", min_samples_leaf=5     |
|          0.885 |         0.01  | n_estimators=320, max_features="log2", criterion="gini", min_samples_leaf=7     |
|          0.885 |         0.01  | n_estimators=160, max_features="log2", criterion="gini", min_samples_leaf=3     |
|          0.885 |         0.013 | n_estimators=80, max_features="log2", criterion="entropy", min_samples_leaf=3   |
|          0.885 |         0.011 | n_estimators=320, max_features="log2", criterion="gini", min_samples_leaf=3     |
|          0.884 |         0.012 | n_estimators=80, max_features="log2", criterion="gini", min_samples_leaf=13     |
|          0.884 |         0.01  | n_estimators=640, max_features="log2", criterion="gini", min_samples_leaf=1     |
|          0.884 |         0.009 | n_estimators=40, max_features="log2", criterion="entropy", min_samples_leaf=5   |
|          0.884 |         0.011 | n_estimators=320, max_features="log2", criterion="gini", min_samples_leaf=1     |
|          0.883 |         0.013 | n_estimators=160, max_features="log2", criterion="entropy", min_samples_leaf=1  |
|          0.883 |         0.009 | n_estimators=40, max_features="log2", criterion="entropy", min_samples_leaf=13  |
|          0.883 |         0.011 | n_estimators=40, max_features="log2", criterion="entropy", min_samples_leaf=3   |
|          0.882 |         0.01  | n_estimators=80, max_features="log2", criterion="gini", min_samples_leaf=7      |
|          0.881 |         0.011 | n_estimators=80, max_features="log2", criterion="gini", min_samples_leaf=5      |
|          0.881 |         0.013 | n_estimators=80, max_features="log2", criterion="gini", min_samples_leaf=3      |
|          0.881 |         0.012 | n_estimators=40, max_features="log2", criterion="gini", min_samples_leaf=7      |
|          0.88  |         0.01  | n_estimators=40, max_features="log2", criterion="gini", min_samples_leaf=5      |
|          0.88  |         0.009 | n_estimators=20, max_features="log2", criterion="entropy", min_samples_leaf=13  |
|          0.88  |         0.011 | n_estimators=40, max_features="log2", criterion="gini", min_samples_leaf=13     |
|          0.878 |         0.012 | n_estimators=40, max_features="log2", criterion="gini", min_samples_leaf=3      |
|          0.877 |         0.012 | n_estimators=80, max_features="log2", criterion="entropy", min_samples_leaf=1   |
|          0.877 |         0.009 | n_estimators=20, max_features="log2", criterion="entropy", min_samples_leaf=5   |
|          0.877 |         0.012 | n_estimators=20, max_features="log2", criterion="gini", min_samples_leaf=13     |
|          0.876 |         0.01  | n_estimators=160, max_features="log2", criterion="gini", min_samples_leaf=1     |
|          0.875 |         0.011 | n_estimators=20, max_features="log2", criterion="entropy", min_samples_leaf=7   |
|          0.875 |         0.014 | n_estimators=20, max_features="log2", criterion="gini", min_samples_leaf=7      |
|          0.873 |         0.009 | n_estimators=20, max_features="log2", criterion="gini", min_samples_leaf=5      |
|          0.872 |         0.012 | n_estimators=20, max_features="log2", criterion="entropy", min_samples_leaf=3   |
|          0.872 |         0.011 | n_estimators=10, max_features="log2", criterion="entropy", min_samples_leaf=13  |
|          0.871 |         0.01  | n_estimators=80, max_features="log2", criterion="gini", min_samples_leaf=1      |
|          0.87  |         0.011 | n_estimators=10, max_features="log2", criterion="gini", min_samples_leaf=13     |
|          0.868 |         0.007 | n_estimators=10, max_features="log2", criterion="entropy", min_samples_leaf=7   |
|          0.864 |         0.01  | n_estimators=10, max_features="log2", criterion="gini", min_samples_leaf=7      |
|          0.863 |         0.014 | n_estimators=40, max_features="log2", criterion="entropy", min_samples_leaf=1   |
|          0.862 |         0.014 | n_estimators=40, max_features="log2", criterion="gini", min_samples_leaf=1      |
|          0.862 |         0.007 | n_estimators=20, max_features="log2", criterion="gini", min_samples_leaf=3      |
|          0.858 |         0.011 | n_estimators=10, max_features="log2", criterion="entropy", min_samples_leaf=5   |
|          0.858 |         0.009 | n_estimators=10, max_features="log2", criterion="gini", min_samples_leaf=5      |
|          0.852 |         0.011 | n_estimators=10, max_features="log2", criterion="entropy", min_samples_leaf=3   |
|          0.844 |         0.01  | n_estimators=10, max_features="log2", criterion="gini", min_samples_leaf=3      |
|          0.844 |         0.011 | n_estimators=20, max_features="log2", criterion="gini", min_samples_leaf=1      |
|          0.842 |         0.017 | n_estimators=20, max_features="log2", criterion="entropy", min_samples_leaf=1   |
|          0.807 |         0.012 | n_estimators=10, max_features="log2", criterion="entropy", min_samples_leaf=1   |
|          0.8   |         0.015 | n_estimators=10, max_features="log2", criterion="gini", min_samples_leaf=1      |

## LogisticRegression
|   mean(scores) |   std(scores) | params              |
|---------------:|--------------:|:--------------------|
|          0.878 |         0.01  | C=10, penalty="l1"  |
|          0.878 |         0.01  | C=1, penalty="l1"   |
|          0.873 |         0.01  | C=0.1, penalty="l1" |
|          0.837 |         0.013 | C=1, penalty="l2"   |
|          0.837 |         0.009 | C=0.1, penalty="l2" |
|          0.831 |         0.015 | C=10, penalty="l2"  |

## GaussianNB
|   mean(scores) |   std(scores) | params   |
|---------------:|--------------:|:---------|
|          0.821 |         0.005 |          |

