# masterthesis_results
This repo contains all computed results of the feature selection, hyperparameter tuning and classification

### Feature Selection Lists
`feature_lists/` contains directories for the different chunk sizes that include files with all features ranked by their importance for filter approaches (ANOVA, Fisher score, Relief-F) or the selected features only for wrapper approaches (RFE). The `.npy` files are used by the code, the `.csv` files contain the same lists and can be previewed more easily.

### Feature Selection Results
`feature_selection_results/` contains directories for the different chunk sizes including files for each feature selection method and feature set. In case of filter methods (ANOVA, Fisher score, Relief-F) each file contains the number of selected features in steps of 5 and the corresponding results calculated on a validation set.

### Hyperparameter and Classification Results
`hyperparam_classification_results/` contains directories for the different chunk sizes including files for each feature set and its best performing feature selection method. The files contain the selected hyper parameters, the classification results on the chunk level for a testing set and the classification results on the infant level using different thresholds.
