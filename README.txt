Download github repository: https://github.com/arthurshime3/UnsupervisedLearning

Original datasets can be found at the following locations:
Titanic Dataset
https://www.kaggle.com/dmilla/introduction-to-decision-trees-titanic-dataset?fbclid=IwAR2wDL2sOlU1vRf4QY8h-FmWbXe0fb_S_dKrLDzzPrGeOJVjg4LvANazzLc
Adult Dataset
http://archive.ics.uci.edu/ml/datasets/Adult?fbclid=IwAR0lRjGu57NmSSrwT2F4UqH-9hyvtJrq9yGdzoUo8QsawnKgo7660AqD5Uw

The preprocessed data is already included in this repository so those can be downloaded and used instead of going to the original websites and downloading the datasets.

Download the datasets from the repository. (Titanic: RandomTit.arff, Adult: adultrandomized.arff)

Open the datasets in Weka and run the following clustering algorithms:
K Means
EM

Then run the following dimension reduction algorithms:
PCA
ICA
Random Projection
Info Gain

Save the reduced datasets and re-run the clustering algorithms on the reduced datasets.

In Weka, run the reduced and clustered data through a multilayer perceptron using the default settings.