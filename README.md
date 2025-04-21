######Image Classification using Bag of Visual Words (BoVW)

In this notebook, we will classify the images into five categories (aeroplane, backgrounds, car, horse, motorcycle, person) using Bag of Visual Word (BoVW) and Support Vector Machine (SVM).

We will extract the SIFT descriptors from the images and construct a codebook. After that, we will encode the images to histogram features using codebook, and train the classifier using those features.

We will then extract dense SIFT descriptors from the images, reconstruct the codebook, then train the classifier again using the new codebook. Then using this codebook we will also test the performance of spatial pyramid matching by training the classifier using that method

Finally, we will use Non-Linear SVM to train the classifier, and test its performance with it.
