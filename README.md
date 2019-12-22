# NeuralNetworkVBA
VBA implementation of neural network

All code in one class module "NeuralNetwork.cls".
Interface has 2 public primary methods: Training and Predict.

* Trainining( Double(), Double() ) - we need run method for each trainingset. First array is input data, second array is expected data. After last trainingset we go to up of loop and again run, while average quad error is not less of minimum. Each round of this trainingsets is Epoch. We neen run over ~ 10K-100K epoches to get true result.

* Predict(Double()) As Double() - this method only forward input data (signal) in network and return result (prediction).

In excel file we have test task: converter of binary number to decimal presentation.
