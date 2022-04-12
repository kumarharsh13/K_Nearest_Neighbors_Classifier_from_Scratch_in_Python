# Heart Attack Prediction from K-Nearest-Neighbors Classifier from Scratch using Python

## Supervised Learning: 
Supervised learning is a sort of machine learning in which machines are taught with well-labeled training data and then predict the output based on that data. The labelled data indicates that part of the input data has already been tagged with the appropriate output. In supervised learning, the training data presented to the machines acts as a supervisor, instructing the machines on how to accurately anticipate the output. A supervised learning algorithm's goal is to discover a mapping function that will translate the input variable(x) to the output variable(y).

## Classification Algorithm: 
The Classification algorithm is a Supervised Learning approach that uses training data to determine the category of fresh observations. Classification is the process of a software learning from a dataset or observations and then classifying fresh observations into one of many classes or groupings. Yes or No, 0 or 1, Spam or Not Spam, cat or dog, and so on. Targets/labels or categories are all terms that may be used to describe classes.

## K-Nearest-Neighbors Classifier:
Learning approach and is one of the most basic Machine Learning algorithms. The K-NN method assumes that the new case/data and existing cases are comparable and places the new case in the category that is most similar to the existing categories. The K-NN method saves all available data and classifies a new data point based on its similarity to the existing data. This implies that fresh data may be quickly sorted into a well-defined category using the K-NN method. The K-NN approach may be used for both regression and classification, however it is more commonly utilised for classification tasks. The K-NN algorithm is a non-parametric algorithm, which means it makes no assumptions about the underlying data.

## Implementaion: 
In our implemantion, we will be finding the distance between the new data_instance. From there we will be findind the K nearest point and from that k points we will be categorizing the class of the new instance.

**Steps followed:** <br>
<ul>
    <li>Create a class for implementation.</li>
    <li>Defined a distance metric function for getting the distance via anyone of the two methods i.e. (Euclidean Distance and Manhattan Distance)</li>
    <li>Defined a nearest neighbor function for training the dataset and finding the k shortest distance from the neighbor list.</li>
    <li>Defined a prediction function which predicts the target values of the given metric.</li>
    <li>After performing this steps we would be calculation the accuracy score and we will compare the accuracy score with the inbuilt KNN Classifier Algorithm.</li>
</ul>

## Summary: 
<ul>
    <li>Total Attributes: 12</li>
    <li>Number of instance: 918</li>
    <li>Accuracy Score: 61.41%</li>
    <li>View Notebook</li>
</ul>