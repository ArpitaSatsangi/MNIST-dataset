# MNIST-dataset

* The dataset is called MNIST and refers to handwritten digit recognition. 
* The dataset provides 70,000 images (28x28 pixels) of handwritten digits (1 digit per image).
* The goal is to write an algorithm that detects which digit is written. Since there are only 10 digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9), this is a classification problem with 10 classes.
* Our goal would be to build a neural network with 2 hidden layers.

  ## Terminology
  * Gradient Descent - It is an iterative optimization algorithm used in machine learning to find the best results (minima of a curve).
  Gradient means the rate of inclination or declination of a slope.
Descent means the instance of descending.

  * Epochs - One Epoch is when an ENTIRE dataset is passed forward and backward through the neural network only ONCE.

  * Batches - Since one epoch is too big to feed to the computer at once (you can’t pass the entire dataset into the neural net at once), we divide dataset into Number of Batches or sets or parts.

  * Iterations - It is the number of batches needed to complete one epoch.


* We can divide the dataset of 2000 examples into batches of 500 then it will take 4 iterations to complete 1 epoch.


  
