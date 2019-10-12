<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

# Part2: Neural Networks and Deep Learning
### Chapter10: Intruduction to Artificial Neural Network
#### 1. artificial neuron:
![artifical neuron](./images1/artificial_neuron.png)
#### 2. The perceptron:
- The Perceptron is one of the simplest ANN architectures. It is based on a slightly different artificial neuron called a *linear threshold unit* (LTU): the inputs and output are now numbers (instead of binary on/off values) and each input connection is associated with a weight. The LTU computes a weighted sum of its inputs: $(z = w_1x_1+w_2x_2 + .....w_nx_n = \bm{w^T\cdot{x}})$ ,then applies s step function to that sum and outputs the result: $h_w(\bm{x}) = step(z) = step(\bm{W^T\cdot{x}})$
![Linear threshold unit](./images1/linear_threshold_unit.png)
- The most common step function used in Perceptrons is the *Heaviside step function*, sometimes the sign function is used instead.
![step function](./images1/step_function.png)


