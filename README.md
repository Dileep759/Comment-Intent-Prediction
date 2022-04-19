# Comment-Intent-Prediction
**Objective:** To create a model which able to predict intents of a sentence. There will be four kind of intents will be there
seller, buyer, neutral and seller buyer. The data is unlabeled having noise data and different types of
sentences are present having links and other description.

**Process:** 1. Did initial pre-processing and EDA.
             2. Label encoded clean text data and nlp cleaned noicy text variables
             3. Splitted dataset into train and test then did TfidfVectorization
             4. Used KMEANS ELBOW method to find out the clusters and then assigned label centers as a Label to unlabeled dataset
             5. Listed the top most occuring words and message samples from each cluster and ascertained intents from those clusters
             6. Finally used DTC to train the model on new labels and to do prediction from test dataset.
