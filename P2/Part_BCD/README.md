### part B, C, D) ####

Our Neural network code is inspired by Morten Hjorth-Jensen's code at https://compphysics.github.io/MachineLearning/doc/pub/week41/html/week41.html.

The code is altered to allow for different activation functions and weight initialization method (Xavier) as well as a flexible number of hidden layers.
It also works on both regression and classification problems.
The number of nodes for each hidden layer is the same.

There are some issues with the code that we have not been able to debug with the given time. There are also some implementations that we would have liked to test on the datasets and put in the report, but due to a lack of time, we prioritized the report, and with that,presenting the code as is. GD is the only optimizer, and could have increased the overall performance, even with the bugs at hand.  