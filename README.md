# ConvNet-for-SVHN

IPython notebook for classifying 32x32 pixel Google Street View House Number (SVHN) images
(see http://ufldl.stanford.edu/housenumbers/) using a convolutional neural network (CNN) model 
with a logistic-regression based classifier as the final step.

The script and model is based on the tutorial found at http://deeplearning.net/tutorial/lenet.html
and adapted for this particular data set. 

Gives accuracy of around 88% for <=500 epochs.  More epochs may improve accuracy but it seems to plateau

Adjusting filter widths may have some impact.  
