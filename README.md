# LncRNA_Sub-cellular_Localisation_Prediction_using_Multi-source_Features

Here in this project we have developed and tested several machine learning models based on multi-source features for the lncRNA sub-cellular localisation prediction. 

First the dataset was collected from the extensive databases search of lab validated lncRNA sub-celullar localisation data. A total of 7 locations dataset was found.

Different set of features were extracted from the sequences such as sequences-based features, structre features and physico-chemical features.

then to reduce the dimension and redundant features several feature selection methods were employed to reduce the chances of overfitting.

9 different machine learning algorithms were used to train and test and ROC curve and other COnfusion matrix based metrices used to find the best model, in our case was Random forest.

Files Descriptions:
1. Dataset_of_7_classes.fasta - Contains the sequences of the lncRNAs with their locations labelled
2. Features_extraction_all.ipynb - Contains the code to extract all the features used in the study from the input fasta file
3. Feature_selection.ipynb - Contains the code for the feature selection methods used in our study
4. All_machine_learning_models.ipynb - Contains the code to train, test all the models  

