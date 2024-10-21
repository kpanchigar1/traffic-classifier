I experimented with the effect of the number of times you do convolution and pooling.
Only convolution the image and pooling the image once gave an accuracy of approximately 0.12.
However, adding another layer of convolution and pooling massively improved the accuracy to 0.96.\
\
I then experimented with changing the size of the hidden layer. Doubling the size of the hidden layer from 128 to 256 did not have a significant impact on the accuracy.\
\
Then, I tried adding another hidden layer of size 128 which did not have much effect on the accuracy. In fact, based on my test, it slightly reduced the accuracy.
