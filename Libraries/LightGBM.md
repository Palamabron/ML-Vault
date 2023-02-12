#library
Light Gradient Boosting Machine

In short: is fast and almost as effective as [[XGBoost]]

It uses:
GBT (GRADIENT BOOSTING TREE)
GBDT (GRADIENT BOOSTING DECISION TREE)
GBRT (GRADIENT BOOSTING REGRESSION TREE)
GBM (GRADIENT BOOSTING MACHINE)
MART (MULTIPLE ADDITIVE REGRESSION TREES)
RF (RANDOM FORESTS)

It implements:
sparse optimization
parallel training
multiple loss functions
regularization
bagging
early stopping

IT GROWS LEAF-WISE (DEPTH-WISE)

IT UTILIZES TWO NOVEL TECHNIQUES (Gradient-Based One-Side Sampling {GOSS} and Exclusive Feature Bundling {EFB})

GOSS excludes large proportion of data instances with small gradients and only use the rest to estimate the information gain

EFB reduces dimentionality of data (especially useful with exclusive features like One-hot encoded features)