# Neural-Style-Transfer

Original Paper : https://arxiv.org/abs/1508.06576

Two images are input to the neural network: A content-image and a style-image. The objective is to generate a mixed-image which has the contours of the content-image and the colours and texture of the style-image. This is donrby creating several loss-functions that can be optimized.

The loss-function for the content-image tries to minimize the difference between the features that are activated for the content-image and for the mixed-image, at one or more layers in the network. This causes the contours of the mixed-image to resemble those of the content-image.

The loss-function for the style-image is slightly more complicated, because it instead tries to minimize the difference between the so-called Gram-matrices for the style-image and the mixed-image. This is done at one or more layers in the network. The Gram-matrix measures which features are activated simultaneously in a given layer. Changing the mixed-image so that it mimics the activation patterns of the style-image causes the colour and texture to be transferred.


TO DO:
GAIN A MORE CLEAR UNDERSTANDING OF A GRAM MATRIX
TRY TO USE DIFFERENT LAYERS AND CHECK IF BETTER RESULTS ARE OBTAINED
