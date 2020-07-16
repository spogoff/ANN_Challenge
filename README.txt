* Neurons and Layers

** The first model has 76 neurons in the first layer and 20 neurons in the second layer. The number of the neurons in the first layer are twice as many as the number of features. The optimized model has 97 neurons in the first hidden layer (3 times as many as the features), 20 in the second layer and 5 in the 3rd layer. 


* The model was optimized in a few different ways: 

** 
    - Layers and neurons - added one more layer and more neurons to each layer
    - Epochs in training - the first model was tested first on 100 and then 500 additional epochs, the optimized model was trained       on 300 epochs
    - Optimizer - the optimizer was changed from "adam" to "adadelta" in the optimized1 model

The model never achieved the desired 75% accuracy rate. However, its performance was improved to 74% when optimized with one additional layer and more neurons. More epochs and different optimizer in the model did not improve the performance. 

* Alternative classifiers

** Random Forest Classifier could have been a good alternative, as it could take large number of features and create a robust model for either classification (what we need in this case) or regression outputs. This model achieved an accuracy of 74% on this data.
