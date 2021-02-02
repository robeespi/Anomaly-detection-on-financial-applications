# Fraud-detection-on-accounting-financial-systems

Problem:
Existing unsupervised fraud detection methods successfully learn representations of normal-anomaly accounting statements offering acceptable interpretability of these models. However, fraudster always Kinds ways to violate known scenarios leading unsupervised approaches to suboptimal performance. 

Solution:
This repo contains a notebook with a solution which proposes the following workflow before to apply a Multilayer Perceptron Neural Network

![alt text](https://github.com/robeespi/Fraud-detection-on-accounting-financial-systems/blob/master/Data_preparation_workflow.jpeg)

# Highlights workflow

PCA helps to visualize two types of fraud on high dimensional data. According to the domain knowledge, by having two types of anomalies make sense

* Global Anomalies: 
Financial statementes that exhibit unusual or rare individual attribute values. These anomalies usually relate to highly skewed attributes e.g. seldom posting users, rarely used ledgers, or unusual posting times.

* Local Anomalies: 
Financial statementes that exhibit an unusual or rare combination of attribute values while the individual attribute values occur quite frequently e.g. unusual accounting records.

Also, t-sne was developed on tensorboard tow visualize fraud objects. The following link shows this https://youtu.be/dR1_WrjaFFE

# Results
