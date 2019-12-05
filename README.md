# Vdub-Recognition

##Problem Statement

I'm always being asked by family and friends for advice when buying new cars. Walking through grocery store parking lots my mother will ask "What is that one? I want that one..." in reference to the shiny new Volkswagen Atlas. Using computer vision models i'd like to create a system for identifying vehicles with a simple picture of it.


##Executive Summary
The purpose of this project is to use a convolution neural network to identify and classify vehicles from photographs. Although the model is simple at this time, it includes Conv2D, Dense, and MaxPooling2D layers. ImageDataGenerator was used in the preprocessing of the images. Preprocessing consisted of shifts, tilts, zooms, flips and more.


##Data
I used a pre-built google image scraper to gather images from 6 different Volkswagen models over a couple of model years. All models were current Volkswagen of America models and are on the road today. 2199 photos were used in the training and validating of the model.

Models("categories") included :

2015-2018 Volkswagen Golf, GTI, R
2014-2017 Volkswagen Jetta, GLI 2013-2016 Volkswagen Tiguan
2018-2020 Volkswagen Atlas
2014-2017 Volkswagen Passat
2016-2019 Volkswagen Golf Sportwagen, Alltrack

https://github.com/hardikvasa/google-images-download

##Conclusion

Although the model was simple and just a proof of concept it performed with an accuracy score of 69%. Baseline score is roughly 22% I think there's an immense amount of room for improvement and I'm extremely excited to continue working on this model and future improvements.
