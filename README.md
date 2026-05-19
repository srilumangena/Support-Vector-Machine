# Support-Vector-Machine
Compare Support Vector Machines (SVMs) trained
using different variants of Stochastic Gradient Descent (SGD) and approximate kernel
methods. The emphasis is on understanding the trade-offs between accuracy, runtime,
and resource usage.
– compare vanilla SGD, SGD with momentum, and Adagrad, both in
– Online mode (one datapoint per update) and Mini-batch mode, with varying
batch sizes (e.g., 8, 32, 128)
Evaluate how these settings impact:
– Convergence speed (passes through the data)
– Training time
– Accuracy
To explore nonlinear decision boundaries at scale, you will implement Random Fourier
Features (RFFs) to approximate kernelized SVMs efficiently.

– use RFFs to approximate the RBF kernel,
– study the effect of the number of features on accuracy, training time, and memory
use, and
– compare the performance of these models to the linear SVMs from Part 1.
