# Data Science Notes

SOTA Models

<!--
Supervised Learning slide- 
Real Estate, Online Ads- NN
Photo Tagging- CNN
Speech Recognition, Machine Translation- RNN
Autonomous Driving- Custom/Hybrid
https://www.coursera.org/learn/neural-networks-deep-learning/lecture/2c38r/supervised-learning-with-neural-networks

https://services.google.com/fb/forms/cloud-tpu-beta-request/

Image Classification
ResNet-50 (image classification)
Other ResNet models (image classification)
MobileNet (low-resource image classification)
SqueezeNet (low-resource image classification)
NASNet-Mobile (low-resource image classification)
NASNet-Large (image classification)
AmoebaNet (image classification)
Inception v2 (image classification)
Inception v3 (image classification)
Inception v4 (image classification)
Inception-ResNet-v1 (image classification)
Inception-ResNet-v2 (image classification)
VGG (image classification)
RevNets (image classification)
DenseNet (image classification)
Shake-Shake (CIFAR image classification)

Image Segmentation
Mask R-CNN (image segmentation)
DeepLab (image segmentation)

Recurrent Neural Networks (RNNs)
LSTM-based models (recurrent neural networks)
Other RNNs (recurrent neural networks)

Object Detection
Faster R-CNN (object detection) 
Single Shot MultiBox Detector (object detection)
R-FCN (object detection) 
RetinaNet (object detection)

Transformer
Transformer (machine translation)
Transformer (language modeling)
Transformer (sentiment analysis)
Transformer (speech recognition) 

Speech Recognition
DeepSpeech 2 (speech recognition)
Other speech recognition models

DeepVariant (genomic variant-calling) 
Generative adversarial networks (GANs)
Other convolutional neural networks on image-like data
Fully-connected neural networks with embeddings
Fully-connected neural networks without embeddings
None of the above
-->

<!--
Linear/Regression (Supervised Learning)
* [Regression (Excel) Wikipedia](http://en.wikipedia.org/wiki/Regression)  
* [Regression Analysis Series (Excel) Wikipedia](http://en.wikipedia.org/wiki/Regression_analysis)  
* [Linear Regression (Best Fit Line) (Excel) Wikipedia](http://en.wikipedia.org/wiki/Linear_regression)  
* [Simple Linear Regression Wikipedia](http://en.wikipedia.org/wiki/Simple_linear_regression)  
* [Linear Function Wikipedia](http://en.wikipedia.org/wiki/Linear_function)  

y = mx + b
y = wx + b

https://en.wikipedia.org/wiki/Linearity | Linearity - Wikipedia
https://en.wikipedia.org/wiki/Nonlinear_system | Nonlinear system - Wikipedia
https://en.wikipedia.org/wiki/Supervised_learning | Supervised learning - Wikipedia
https://en.wikipedia.org/wiki/Unsupervised_learning | Unsupervised learning - Wikipedia
https://en.wikipedia.org/wiki/Reinforcement_learning | Reinforcement learning - Wikipedia

https://en.wikipedia.org/wiki/Unstructured_data | Unstructured data - Wikipedia
https://en.wikipedia.org/wiki/Data_processing
Data Normalization

https://en.wikipedia.org/wiki/Sensitivity_and_specificity
https://en.wikipedia.org/wiki/Precision_and_recall

https://en.wikipedia.org/wiki/Feature_vector
https://en.wikipedia.org/wiki/Feature_scaling
https://en.wikipedia.org/wiki/Feature_engineering

Classification vs. Regression
Linear Regression vs. Logistic Regression
Linear Regression Loss Function = Squared Loss
Logistic Regression Loss Function = Log Loss

https://en.wikipedia.org/wiki/Regression_analysis | Regression analysis - Wikipedia
https://en.wikipedia.org/wiki/Linear_regression | Linear regression - Wikipedia
https://en.wikipedia.org/wiki/Logistic_regression | Logistic regression - Wikipedia

Improving Deep Neural Networks
https://www.coursera.org/learn/deep-neural-network/home/welcome

Improving the way neural networks learn
http://neuralnetworksanddeeplearning.com/chap3.html
-->

Normalizing Inputs/Feature Scaling

<!--
https://en.wikipedia.org/wiki/Feature_scaling | Feature scaling - Wikipedia
-->

Weight Initialization

Activation Functions

<!--
https://en.wikibooks.org/wiki/Artificial_Neural_Networks/Activation_Functions | Artificial Neural Networks/Activation Functions - Wikibooks, open books for an open world
https://en.wikipedia.org/wiki/Activation_function | Activation function - Wikipedia

https://en.wikipedia.org/wiki/Rectifier_(neural_networks) | Rectifier (neural networks) - Wikipedia
Softmax Regression- Multi-Class Classification
https://en.wikipedia.org/wiki/Softmax_function | Softmax function - Wikipedia
https://en.wikipedia.org/wiki/Sigmoid_function | Sigmoid function - Wikipedia
https://en.wikipedia.org/wiki/Hyperbolic_function#Hyperbolic_tangent | Hyperbolic function - Wikipedia
http://reference.wolfram.com/language/ref/Tanh.html
http://mathworld.wolfram.com/HyperbolicTangent.html
-->

Bias-Variance Tradeoff

<!--
https://en.wikipedia.org/wiki/Bias%E2%80%93variance_tradeoff | Bias–variance tradeoff - Wikipedia
-->

Loss/Cost Function

<!--
Loss/Cost Function
https://stats.stackexchange.com/questions/154879/a-list-of-cost-functions-used-in-neural-networks-alongside-applications/154880 | machine learning - A list of cost functions used in neural networks, alongside applications - Cross Validated

https://en.wikipedia.org/wiki/Loss_function | Loss function - Wikipedia
Squared Error
https://en.wikipedia.org/wiki/Mean_squared_error (a.k.a. Quadratic Cost Function
Cross-Entropy Cost Function
https://en.wikipedia.org/wiki/Cross_entropy#Cross-entropy_error_function_and_logistic_regression
-->

Optimizing Gradient Descent

<!--
https://en.wikipedia.org/wiki/Derivative | Derivative - Wikipedia
https://en.wikipedia.org/wiki/Backpropagation
https://en.wikipedia.org/wiki/Chain_rule | Chain rule - Wikipedia
https://en.wikipedia.org/wiki/Gradient | Gradient - Wikipedia
http://ruder.io/optimizing-gradient-descent/ | An overview of gradient descent optimization algorithms
https://en.wikipedia.org/wiki/Gradient_descent | Gradient descent - Wikipedia
https://en.wikipedia.org/wiki/Stochastic_gradient_descent
Batch and mini batch gradient descent
Gradient descent with momentum
Exponentially weighted averages
RMSProp
Adam Optimization
AdaGrad
-->

Batch Norm (Usually Mini-Batches)

Regularization

<!--
Regularization Rate
https://en.wikipedia.org/wiki/Regularization_(mathematics)
L0 Regularization
L2 Regularization
L1 Regularization/L1 Weight Decay
Dropout
https://en.wikipedia.org/wiki/Early_stopping | Early stopping - Wikipedia
-->

Hyperparameters

<!--
General Importance

1- Learning rate alpha

2- Momentum term beta
3- Mini-batch size
4- # of hidden units

5- # of layers
6- Learning rate decay

Adam- Beta 1, Beta 2, Epison
-->

Learning Rates/Learning Rate Decay Methods 

Grad Check

<!--
grad check doesn't work with dropout
only use grad check when debugging 
-->
