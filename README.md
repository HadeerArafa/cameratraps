# cameratraps DataSet
# intro
- Here you have a lot of images from camera traps located at different sites. There are seven types of critters captured in this set of images: birds, civets, duikers, hogs, leopards, other monkeys, and rodents. There are also images that contain no animals (blank).

- Each record in the dataset corresponds to a single image captured by a camera. Each record has one .jpg file associated with it in either the train_features or test_features directory, depending on which dataset it is a part of. Each image is accompanied by additional information in train_set.csv and test_set.csv.

# Files
- train_set.csv - containing the image name and its path and site
- train_labels.csv - containing the label (the class) of each image
- test_set.csv - containing the image name and its path and site
- sample_submission.csv - a sample submission file in the correct format
- train_features - the directory that contains the training images
- test_features - the directory that contains the test images

# Columns
- id - a unique identifier for each image
- filepath - image path including its split directory (train or test)
- site - the site in which the image was taken

# Note :
There is no overlap between the sites in the training data and the sites in the testing data, which means that the model you build must perform well in new contexts. You may use this 'site' feature to create your own train and test set with disjoint sites to make sure your model can make good predictions on sites it has not been trained on.
