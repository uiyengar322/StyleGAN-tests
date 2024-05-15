# StyleGAN-tests

StyleGAN exploration on new landscape and city image datasets. 
Code from Keras.io/Keras GitHub repository,
Source: https://github.com/keras-team/keras-io/blob/master/examples/generative/stylegan.py
Licensed under the Apache License, Version 2.0, which is also included.

Added FID and IS evaluation metrics as well as a base evaluation of both datasets done with a DCGAN. The files are named based on the evaluated dataset as well as the number of steps per epoch and altered learning rates for a few files (everything else is the same between the different files). There are multiple generated images displayed, and some files also have additional experimentation with style mixing between two given generated images as well as noise mixing (where noise alterations in one generated image result in variations of that image). Although the results show improvements when increasing the number of steps per epoch in most cases, the StyleGAN results are still limited by dataset size and resource availability (growth of the model was limited to 64x64). There is also a references file which contains relevant publications and the dataset references.
