# Project: Can you recognize the emotion from an image of a face?

### Output folder

The baseline.p and advanced.p files contain the train baseline and advanced models respectively.

The fiducial_pt_list.p file is a list of the pairwise fiducial points from the training data.

The model_results.p file contains the results of the feature extraction train time, feature extraction test time, train time, prediction time, accuracy, balanced accuracy, and AUC for the baseline, advanced, and all other model candidates.

The remaining .pbz2 files are train/test data contain different types of features from the functions in the feature.ipynb file. In particular, train_data_initial and test_data_initial are made from the initial starter code features, train_data and test_data are made from our improved features, train_data_SMOTE is made from applying SMOTE to the improved features, and both train_data_PCA and test_data_PCA are obtained from applying PCA to the improved features.
