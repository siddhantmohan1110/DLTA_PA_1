# DLTA_PA_1
Deep Learning Theory &amp; Applications - Programming Assignment 1

The file "mnist.ipynb" executes the k-nearest neighbour classification algorithm on a subset of the MNIST dataset containing 1000 training images and 100 test images after converting each 28\*28 grayscale image into a 784\*1 vector.

The file "cifar10.ipynb" executes the k-nearest neighbour classification algorithm on a subset of the CIFAR-10 dataset containig 1000 training images and 100 test images after converting each 32\*32\*3 RGB image into a histogram of pixel intensities. We obtain a 768\*1 vector of each image where the first 256 rows represent the occurence of each pixel intensity in the red image, followed by 256 rows each for the green and blue images.

The confusion matrix and accuracy score is computed for both tasks.

The datasets are present in "mnist.pt" and "cifar10.pt".
