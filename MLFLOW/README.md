## This Notebook is Regrading Fashionmnist data by Using ANN and MLFlow
[Dataset link](https://www.kaggle.com/datasets/zalando-research/fashionmnist)
#### Note:In Tensorflow library we have BuiltIn dataset for fashionmnist
## What is MLFLow?
* It is a open source platform for machine learning lifecycle.
### [MLflow documnetation](https://www.mlflow.org/docs/latest/index.html)
## Dataset Information:

* Dataset consists of 700000 rows and (28*28==784) columns
* Target Class is having  nine different classes which is  marked from **0 to 9**.
![FashionMnsit](https://machinelearningmastery.com/wp-content/uploads/2019/02/Plot-of-a-Subset-of-Images-from-the-Fashion-MNIST-Dataset-1024x768.png)
## Libraries Used:
* pandas
* numpy
* matplotlib
* seaborn
* tensorflow
* mlflow
* sklearn
## Steps Involved:
1) IMPORTING ALL NECESSARY LIBRARIES
2) LOADING THE DATASET
3) SCALING THE DATASET
4) CREATE A MODEL AND BUILD THE LAYERS
5) MODELLING THE DATASET
6) USING MLFLOW

## OBSERVATIONS

1)Without Applying BatchNormalization and Dropout
  * Activation Function=**Relu**(For Hidden layers)
  * Activation Function=**Softmax**(For Target Class)
  * LOSS_FUNCTION=**sparse_categorical_crossentropy**
  * OPTIMIZER=**RMSProp**
  * METRICS=**accuracy**
  * Accuracy=0.961
  
2) Applying BatchNormalization
  * Activation Function=**Relu**(For Hidden layers)
  * Activation Function=**Softmax**(For Target Class)
  * LOSS_FUNCTION=**sparse_categorical_crossentropy**
  * OPTIMIZER=**RMSProp**
  * METRICS=**accuracy**
  * Accuracy=0.989

3) By Using DropOut
  * Activation Function=**Relu**(For Hidden layers)
  * Activation Function=**Softmax**(For Target Class)
  * LOSS_FUNCTION=**sparse_categorical_crossentropy**
  * OPTIMIZER=**RMSProp**
  * METRICS=**accuracy**
  * Accuracy=0.841

**![Parallel Coordinate Graph](MLFLOW/Comparsion.JPG)

