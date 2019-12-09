# Privacy Project - Stealing Machine Learning Models via Querying

by Qinyu Zhu and Taejin Kim
FA19 Carnegie Mellon University - Foundations of Privacy

### Summary

For this project, we are replicating a portion of the paper "Stealing Machine Learning Models via Prediction APIs (https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_tramer.pdf). We build and attack a classifier model with various attack methods including the equation solving attack, uniform query attack, and adaptive query attack.

### Repo Contents

The following are the contents of this github repository.

#### Data 

- iris.csv: Dataset used for training Neural network
- adult.csv: Dataset used for training logistic binary classifier and decision trees
- adult_encoded.csv: one-hot encoded version of adult.csv
- One Hot Encoding - Adult CSV.ipynb: notebook used to do one-hot encoding

#### Model Attack Testing

- Binary Classifier 1.ipynb: binary classifier test on iris data
- Binary Classifier 2.ipynb: binary classifier test on adult data
- Decision Tree and Uniform Attack.ipynb: decision tree test on adult data
- Multi-Layer Perceptron Attack 1.ipynb: NN test on adult data
- Multi-Layer Perceptron Attack 2.ipynb: NN test on iris data

#### Model Resilience Testing

- model_stealing.ipynb: Check resilience of models from being stolen by attacks
