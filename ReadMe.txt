In order to run the notebooks, the following structure will be useful.
Files in cluded in the notebook&dat folder, as the name tells, contain notebooks that were ran on colab and 
the feature sets used to run each. The structure is as below:

notebooks&code
|_dataset1
| |_data
| | |_freqFeatures.csv -> frequency features extracted from music of length 20s before splitting to train and test
| | |_timeFeatures.csv -> time domain features extracted from music of length 20s before splitting to train and test
| |
| |_mlProjectClassification_frequencyDomainWithNorm_dataset1.ipynb
| |_mlProjectClassification_frequencyDomainWithoutNorm_dataset1.ipynb
| |_mlProjectClassification_timeDomainWithNorm_dataset1.ipynb
| |_mlProjectClassification_timeDomainWithoutNorm_dataset1.ipynb
|
|_dataset2
| |_data
| | |_freqFeaturesTrain.csv -> frequency features extracted for train from music of length 20s after splitting to train and test
| | |_timeFeaturesTrain.csv -> time domain features extracted for train set from music of length 20s after splitting to train and test
| | |_freqFeaturesTest.csv -> frequency features extracted for test set from music of length 20s after splitting to train and test
| | |_freqFeaturesTest.csv -> time domain features extracted for test set from music of length 20s after splitting to train and test
| |
| |_mlProjectClassification_frequencyDomainWithNorm_dataset2.ipynb
| |_mlProjectClassification_frequencyDomainWithoutNorm_dataset2.ipynb
| |_mlProjectClassification_timeDomainWithNorm_dataset2.ipynb
| |_mlProjectClassification_timeDomainWithoutNorm_dataset2.ipynb
|
|_mfcc
| |_mfccData -> mfcc data extracted from music of length 20s. this is a 2D feature set
| |_mfccLabels -> labels of the coressponding mfcc features
|
|_badFiles.csv -> name of the bad files(not in mp3 format) recognized in the whole dataset
|_mlProjectClustering.ipynb -> clustering done on the first dataset
|_mlProjectDeepLearning_v2.ipynb -> deep learning done on the first dataset and mfcc datset
|_mlProjectFeatureExtraction.ipynb -> deature extraction
