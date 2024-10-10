# Resnet-pretrained-model
This is Face recognition using CNN.It takes images from database, performs feature extraction methods. Then it takes query image database, performs same operations on query images, The closest match is shown as similar matches in display based on  distance.

Overview:
This project consists of a trainmodel.py script for training model and testmodel.py for testing the model. It contains trainsmall and testsmall folders containing database and query images. You also have distance.py to plot distance metrics between inter-class and intra-class features. While running project, first add trainsmall, testsmall and output folders to the project. the file paths of training, testing and an empty directory named output.
Then, run trainmodel.py and next run testmodel.py using Resnet_feature_extractor.
