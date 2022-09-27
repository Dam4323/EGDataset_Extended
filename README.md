# EGDataset Extended

Exploration Global Dataset is a dataset provided by a hybrid model to perform malware detection on Android applications. This dataset is based on a hybrid model (static and dynamic analysis) with an exploration approach.

# Purpose
The approach used to obtain this dataset investigates the general application's features. Then this performs some investigations on the several nodes to analyze the global app behavior.Finally, you can read the result obtained after using deep learning analysis on the dataset and a k-folds approach with ten occurrences.This dataset is an extension of previous EGDataset located at this link : https://github.com/Dam4323/EGDataset

|Algorithms|Accuracy|Precision|Recall|F1_Score|
|---|---|---|---|---|
|Neural Network (MLP Classifier)|0.964|0.963|0.964|0.964|

# Dataset Population

This dataset is composed by 9427 records (461 benigns and 611 malwares). You can see the statistics distribution on this table :

|Adware|Banking|Ramsonware|Riskware|Scareware|SMS|Total|
|---|---|---|---|---|---|---|
|1119|690|50|3177|86|4305|9427|

Be careful, this dataset has not got any benignware. It is based on CICandMAL2017 (https://www.unb.ca/cic/datasets/andmal2017.html) version provided by the University of New Brunswick and the addition of "VirusShare" samples

# Neural Network Model

The neural network model used to obtain this result has the following layers composition :

|InputLayer|Hidden1|Hidden2|OutpoutLayer|
|---|---|---|---|
|30|100|100|6|

# Availability
This dataset is under an open-source license, but the model's code is unavailable for privacy reasons. However, if you have any questions before using it, you can contact me by e-mail (damien.strullu@gmail.com) or Linkedin (https://www.linkedin.com/in/damienstrullu/). This dataset is not available for commercial purpose and makes no warranty for such use.

If you use this dataset, thanks to mention this in your work.

# Special Thanks

This dataset is obtained due to the participation of "VirusShare" (https://virusshare.com/) and "The University of New Brunswick" (https://www.unb.ca/) to provide all malware samples.
