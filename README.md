# DS785-Final-Project

This project explored using completely unsupervised and semi-supervised machine learning algorithms to predict anomalies within clickstream variables. 
I found that https://scikit-learn.org/1.5/modules/outlier_detection.html employed most methods after researching past literature on similar problems.

I tested the methods in the "DS 785 Notebook 10-26-24.ipynb" notebook on a sample test set. 
When I attempted to scale the sample size up to the population size, I found only the Isolation Forest Algorithm to be performant in a reasonable amount of time with the resources I had available in my AWS Workspace.

The isolation forest production runs used for the project are found in the "DS 785 Iso Runs 11-14-24.ipynb" notebook. 
