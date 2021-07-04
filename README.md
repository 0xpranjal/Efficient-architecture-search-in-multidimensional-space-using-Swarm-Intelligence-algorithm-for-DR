# Swarm-Research

## Training plan for image models(Without Swarm Optimisation)
* Pretrain models on 2015 dataset and then train on 2019 dataset
* The number of epochs used is yet to be decided
* K-Fold validation on 2019 dataset.
    * Basically, the model would train as it is on 2015 dataset
    * On the 2019 dataset, folds would be used to check for accuracy 
* Total number of images is 35000 + 4000 -> 39000 images.(Cause we got V100, can change this as well)

* Models to be covered
   * Efficientnet B5
   * Resnet 200D
   * **Add in your suggestions here**
 
 ## Deep Swarm
   * Checked for compatibility of Code in TF 2.x using MNIST Pipeline
   * Need to write TF code for loading data for optimisation     

 ## psoCNN
   * Completed pipeline, hopefully works
   * Dataset path to be modified in psoCNN.py
   * Need to decide on hyperparameters 
   * [Reference paper](https://www.sciencedirect.com/science/article/abs/pii/S2210650218309246)
   * Pipeline taken from [here](https://github.com/feferna/psoCNN)
   * [This](https://www.kaggle.com/xhlulu/aptos-2019-densenet-keras-starter) kaggle kernel was also referenced a bit