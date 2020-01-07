# FashionMNIST

Fashion-MNIST is a dataset of Zalando's article images. It consist of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated to with a label from 10 clothing classes. Zalando's Fashion-MNIST seeks to replace the original MNIST dataset for setting the standard machine learning algorithms. It shares the same image size and structure of training and test datasets.

The original MNIST dataset has handwritten digits while Fashion-MNIST has differentiated clothing items from 10 different classes. This dataset is very popular among members of the AI/ML/Data Science community, and most members use it as a point of reference to support their algorithms.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value (intensity) associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels, and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.
