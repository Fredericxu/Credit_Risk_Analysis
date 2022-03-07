# Credit_Risk_Analysis
## Overview
Oversample the data using the RandomOverSample and SMOTE algorithms and also undersample the data using the ClusterCentroids algorithm.Also compare the machine learning models to predict credit risks.

## Processing the data and Comparasion:
1. credit_risk_resampling.ipynb includes all three algorithm performed with accuracy score, confusion matrix and imbalanced classification.
2. redit_risk_ensemble.ipnb includes the accuracy_score and confusion matrix and imablanced classification for balancedRandomForestClassifier and EasyEnsembleClassifier
### Comparasion:

1. EE Classifier
![EEClassifier](https://user-images.githubusercontent.com/93050182/156961405-07c90711-8e3f-4656-9b46-4605ab3dccd1.png)
2. BRF Classifier
![Blanced RandomForestClassifier](https://user-images.githubusercontent.com/93050182/156961437-ff5c86ef-abee-4972-af1c-6c277635e220.png)
3. Smote
![SMOTE](https://user-images.githubusercontent.com/93050182/156961509-bcc9f94d-ef6f-4526-8a9a-3a46ec63d628.png)

5. SMOTEEEEEEN
![SMOTEEEEEEEN](https://user-images.githubusercontent.com/93050182/156961519-8af010dc-569f-4718-a828-43dfab2cf55d.png)

6. CC
![ClusterCentroids](https://user-images.githubusercontent.com/93050182/156961548-64fc9dbd-8ade-4d57-9636-01ae56c54fc2.png)

7. ROS
![RandomOverSample](https://user-images.githubusercontent.com/93050182/156961571-84e3d6a0-8c0e-4d32-8a1b-58eabe0d11fe.png)

## Conclusion
Since the EasyEnsembleClassifier has the highest score (with 0.94 in weighted avg) so that this method is the most accurate & effective one.
