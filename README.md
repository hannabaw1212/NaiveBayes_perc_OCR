# NaiveBayes_perc_OCR

 this project is on Optical Character Recognition (OCR) using the Naive Bayes and Perceptron algorithms. The goal of this project is to convert images of handwritten digits (0-9) into their digital representation.
The dataset provided includes three sets of digit images for training, validation, and testing, as well as their corresponding labels, as identified by human taggers. Each digit image is represented by a 28x28 array of pixels, with binary values: 0 for white and 1 for dark pixels. Dark pixels are indicated by '+' or '#' signs.

In this project, I implemented the following steps:

1. Data Preprocessing: Loaded and preprocessed the digit image data and labels for training, validation, and testing.

2. Feature Extraction: Extracted features from the 28x28 pixel arrays to use as inputs for the Naive Bayes and Perceptron algorithms.

3. Model Implementation: Implemented the Naive Bayes and Perceptron algorithms, leveraging the pixel features and corresponding labels to train the models.

4. Model Evaluation: Evaluated the performance of the Naive Bayes and Perceptron models on the validation dataset, tuning hyperparameters as necessary to optimize performance.

5. Testing: Assessed the final models' performance on the test dataset, comparing the accuracy of the Naive Bayes and Perceptron approaches for handwritten digit recognition.

The project demonstrates the application of the Naive Bayes and Perceptron algorithms for OCR, showcasing the ability to recognize and convert handwritten digits into their digital form.
