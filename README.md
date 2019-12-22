# NeuralNetworkVBA
VBA implementation of neural network

All code contained in single class module "NeuralNetwork.cls".
Interface has 2 public primary methods: Training and Predict.

* Trainining( Double(), Double() ) - we need to run method for each trainingset. First array is input data, second array is expected data. After last trainingset we go to up of loop and run again, while average quad error is not less of minimum. Each round of this trainingsets is Epoch. We need to run over ~ 10K-100K epoches to get true result.

* Predict(Double()) As Double() - this method is only for forwarding input data (signal) in network and return result (prediction).

In excel file we have test task: converter of binary number to decimal presentation.
