This project aims to train a classifier to categorize and label images into 10 classes: 

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

Tensorflow and Keras libraries were used to construct and train a neural network having 3 Dense layers. The first 2 Dense layers use a ReLu activation function while the final layer utilizes a softmax activation function that outputs the probability of an image belonging to each class. The class having the highest probability is taken as the image's label.

The final model achieved 94% accuracy in the training set and 86% in the training set (unseen data).
