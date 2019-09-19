# ralogic
Start porting RAL to Pytorch/Tensorflow/MXNet, probably Pytorch. MVP would be nice, context for why it’s harder is ok, do awesome

## environment setup
*.need conda and pip3 and MDAnalysis
conda install tensorflow matplotlib scipy  
pip3 install encodermap

## smoke test: MNest
1. stock images implemented in tensorflow

# activation functions
tanh, relu. sigmoid, leaky relu, softmax, softplus
1. understand functions
2. multidimensional: 
  -CNN convolution (5x5 -> 3x3 etc)
  -RNN recurrence (loops back output from previous predictions in time)
  -turning variable size inputs into a fixed size structure

# further reading
[Activation Functions](https://medium.com/@himanshuxd/activation-functions-sigmoid-relu-leaky-relu-and-softmax-basics-for-neural-networks-and-deep-8d9c70eed91e)

[Tsetlin Machines](https://arxiv.org/abs/1804.01508)

[Tensorflow Playground](https://playground.tensorflow.org/)

