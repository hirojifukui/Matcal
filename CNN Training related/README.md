This folder constists of several ipynb files. 

Keras Training 25x44 for ones digit
   This application trains the CNN to categorize only ones digit. 
   The trained CNN is used with another CNN that categorizes tens digit. 

Keras Training 25x44 for tens digit
   This application trains the CNN to recognize and categorize only tens digit. 
   The trained CNN is used with another CNN that categorizes ones digit.
   If there is only one character, it should recognize 0.

Evaluate images with Single-digit models
   This app evaluate a model that combined above model with the training data. 

Keras Test 25 x 44 to 100
   This app trains the CNN to categorize an image into 100 categories (0 to 99). But no blank cell. 
   Previously used.

Evaluate single image with learned model
   This app evaluate the training images with above app that categorizes into 100 categories.

Multi Labeles Categorization Test
   This app trains SmallerVGGNet to multi_labels Categorization. 
   The performance should be improved drastically by tuning the paramenter. 
   Current paramenters are for 96 x 96 x 3 channels (RGB), and the perormance is not good. 

Evaluate images with multi_labels SmallerVGGNet
   This app evaluate the CNN trained with the above app. 

Generate base fonts to generate 2-digits image
   This app generate the base fonts from scanned images using CV2 and horizontal lines and vertical lines.

Generate multi-digit training data
   This app generate only 2-digit training data from the base fonts. 

Generate single digit training data
   This app generate only 1-digit traning data from the base fonts.