Short description:

IMLO - Intelligent Systems: Machine learning and optimisation assignment

The task was to develop a custom CNN that accepted the Oxford Flowers 102 dataset and trained/ learned on it.
My model uses the cross entropy loss function with the adam optimiser. For the duration of my explanations I will be referring to cross entropy as CE for simplicity. CE works by measuring differences between probability distributions and predicted values. The loss ranges between values of 0 and 1. The value would increase if the actual value is further away from the label. The CE loss is then calculated to measure the difference between the probabilities and predicted values. This loss is propagated back through the network via backpropagation (can be seen in code), computing gradients layer by layer, which updates the model's weights iteratively to minimise the loss. The ideal loss is 0
