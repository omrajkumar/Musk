# Musk
# Pre-processing
In case of preprocessing first i have follow these steps.
  drop 'ID', 'molecule_name','conformation_name' columns.
  Check null value are available or not in dataframe.
  Dropth duplicate values.
  
  then  describe() is used to view some basic statistical details like percentile, mean, std etc. of a data frame or a series     of numeric values. When this method is applied to a series of string, it returns a different output DataFrame.
  count-
   Count number of non-NA/null observations.
  max-
   Maximum of the values in the object.
  min
   Minimum of the values in the object.
  mean
   Mean of the values.
  std
   Standard deviation of the observations.
 

# Post-Processing
The data has to be split in a 80:20 ratio for training and validation datasets.
And,In case of training I have used ANN Multi-Layer Perceptron.
Artificial Neural Networks (ANN) are multi-layer fully-connected neural nets. They consist of an input layer, multiple hidden layers, and an output layer. Every node in one layer is connected to every other node in the next layer. We make the network deeper by increasing the number of hidden layers.


