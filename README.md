# EX2-Images-Classifier

Deep Learning EX2

1)	Run https://www.tensorflow.org/tutorials/keras/classification . This classifier works on fashion items.
2)	Convert it to recognize digits. There is also an minst dataset for digits.
3)	Make modifications to the networks and report the train and test accuracies as you modify the networks.  You can also change the activation function.
4)	Plot a histogram of the accuracies of the test examples for correctly and incorrectly classified objects.
5)	Change the test images and use the other test set (for fashion network test on the digits test dataset and vice versa). Here again plot histograms. How sure are the classifiers when run on the wrong type of data? 
6)	Given a test image for one digit and a test image for another digit generate a set of images
I(alpha) = alpha * I1 + (1-alpha) * I2 for 100 alphas between 0 and 1. Run the digit classifier on these images and plot the results both the classification and the probability of the class. What are your conclusions from that?
7)	Taking the two test images mentioned above, extract the results of the second layer (128 numbers) V1 and V2. Print them. These are the internal representation of the images.
8)	Predict the results of the network using these vectors. That means run the final level only on them. You should get the same results.
9)	Take V1 and V2 and generate 50 vectors, where V(alpha) = alpha * V1 + (1-alpha) *V2, where alpha is between -1 and 2. Plot the probabilities for these two classes for all these values. See what values you get when alpha is far from 0 (digit 1) and 1 (digit 2).

