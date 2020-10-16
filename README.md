# Microbes-Classifier
Classifying Microbes using CNN implemented in keras.
This project classifies microbes images into 14 different classes with an validaton accuracy of 90%.
The architecture is similar to VGG-19 except the inline three convoltional layers are replaced by a single layer of same hyperparameters.
A rather unconventional way is used to train the model here.
It was observed that the accuracy never went above 88% with batch size of 64
The same was observed with batch size of 256
But when first 10 epochs were run on batch size 64 and the next 10 were run on batch size 256, accuracy of 90% was achieved.
