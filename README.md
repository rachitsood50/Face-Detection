# Face-Detection
Face Detection Algorithm focuses on frontal human faces which is analogous to image detection where image of person is matched bit by bit. I'm re-implementing Viola-Jones Algorithm and trying to improve it by changing the wavelet for feature extraction, configuration of cascading structure 
and changing the adaboost algorithm with boosted classifier.  

The folder contains the following named files:
 cascade_detector
 cascade_detector_LBP_prototype
 gabor_extract
 helper
 integral_image
 LBP_image and
 The image set

The Gabor_extract takes image as a input, converts it into an integral image extracting the
features of that image.
 Place the trained data set( as in the zipped folder) in the path mentioned as in the
cascade_detector program and run it using python3.
 It gives all the true positives , true negatives , false positives, false negatives for every
epoch of training.
 Once the model is trained, change the data set to test and run the same program. This
gives the accuracy of the test data set.
 Repeat the same steps as above for cascade_detector_LBP_prototype to train and test
with LBP wavelets.
