# quick draw
"Google has collected a series of hand-drawn images corresponding to a number of categories in their Quick, Draw! project. The dataset used in this project is a modified subset of this dataset. The dataset contains images that aren't always centered and straight, neither are they free of noisy artifacts. Some of the images are composed of just noise, and the classifier need to identify such empty pictures too."

The best neural networks found is a resnet with 10 layers. This resnet alone (i.e. not an ensemble) got an accuracy of 0.64457% on kaggle.
In comparison, the default linear svm from scikitlearn got 0.04733% on kaggle and 0.10966% when the dataset is cleaned. Resnet18 got 0.56542% on kaggle.
