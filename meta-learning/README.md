# Meta Learning 

* Description: Meta-learning is training the models with little amount of data 
* Link: https://lilianweng.github.io/lil-log/2018/11/30/meta-learning.html 

Meta-Learning(learning to learn): Meta-learning deals with finding the best ways to learn from given data i.e learning various optimization settings and hyper-parameters for the model. Note that there are various ways of implementing Meta-Learning and let's discuss one such method. A meta-learning framework typically consists of a network which has two models:

a) A neural network called Optimize or a Learner which is treated as a low-level network and is used for prediction.
b) We have another neural network which is called Optimizer or Meta-Learner or High-Level model which updates the weights of the lower-level network.
