# nature
## [Flood Prediction](nature/Flood_detection.ipynb)
### Motivation :
The flood precaution is a critical issue for any city, any flood happening could bring disastrous result with millions of financial
damage not just for public but also individual.
The notebook also shows the application of distributed system by using Pyspark and Pandas for ensemble learning

### Problem Statement : 
Flood detection refers to the process of identifying, monitoring, and alerting authorities or individuals about the 
presence or likelihood of flooding in a particular area. It involves the use of various technologies and methods to detect, 
predict, and mitigate the impacts of floods. The datasets contains feature such as MonsoonIntensity, TopographyDrainage
RiverManagement in numeric format. 

### result :
Linear model show overfitting result which could not reflect the performance in test datasets, while in training datasets the model
could show 0.83 R2 scores, in testing datasets each model only show 50% accuracy which means the model predict unseen datasets 
randomly


dataset source is from https://www.kaggle.com/competitions/playground-series-s4e5/data


