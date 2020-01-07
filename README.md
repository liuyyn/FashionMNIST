# Fashion-MNIST

## Content
Fashion-MNIST is a dataset of Zalando's article images. It consist of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated to with a label from 10 clothing classes. Zalando's Fashion-MNIST seeks to replace the original MNIST dataset for setting the standard machine learning algorithms. It shares the same image size and structure of training and test datasets.

The original MNIST dataset has handwritten digits while Fashion-MNIST has differentiated clothing items from 10 different classes. This dataset is very popular among members of the AI/ML/Data Science community, and most members use it as a point of reference to support their algorithms.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value (intensity) associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels, and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.

### Objective 
The objective of this project is to create a Machine Learning model to predict which type of clothing from the labels list (see below) the images from the test dataset is associated to. 

## Labels
- 0 T-shirt/top
- 1 Trouser
- 2 Pullover
- 3 Dress
- 4 Coat
- 5 Sandal
- 6 Shirt
- 7 Sneaker
- 8 Bag
- 9 Ankle boot

## Acknowledgement
Original dataset was downloaded from https://github.com/zalandoresearch/fashion-mnist

## License
The MIT License (MIT) Copyright © 2017 Zalando SE, https://tech.zalando.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
© 2020 GitHub, Inc.
