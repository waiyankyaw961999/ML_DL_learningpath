##Building Deep Neural Networks for Fashion-MNIST

`Fashion-MNIST` is a dataset of [Zalando](https://jobs.zalando.com/tech/)'s article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples.

I use Keras API
- [Keras](https://keras.io/datasets/#fashion-mnist-database-of-fashion-articles)

### Labels
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot | 

This is my first attempt to deal with huge amount of datasets using different ANNs architecture. 
With Fashion-MNIST datasets, I would try to figure out train/test accuracy differences using classical networks such as ConvNet, ResNet which I have learned from Coursera Deep Learning Specialization Course.


### Why I start trying with Fashion-MNIST?
Because it can be easily used to train and evaluate the performances of different models (with or without) data preprocessing stage.
You can check other people trying to improve the model accuraccy in the past since 2017.

"If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others." << This inspires me to kick off.
