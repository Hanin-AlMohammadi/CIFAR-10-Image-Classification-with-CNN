# CIFAR-10-Image-Classification-with-CNN
This project demonstrates the implementation of a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 32x32 color images across 10 different categories, such as airplanes, cars, birds, cats, and more.

Key features of the project:

1. Data Loading and Preprocessing: The CIFAR-10 dataset is loaded and normalized to ensure that the pixel values are scaled between 0 and 1. The labels are converted to one-hot encoded vectors for multi-class classification.
2. Model Architecture: A sequential CNN model is built with multiple convolutional layers followed by max-pooling layers, a flattening layer, and dense layers. The model is compiled using the Adam optimizer and categorical crossentropy as the loss function.
3. Model Training and Evaluation: The model is trained on the CIFAR-10 training set for 10 epochs, and its performance is evaluated on the test set. The accuracy of the model is reported, showcasing its ability to classify the images correctly.
4. Visualization: The project includes visualizations of some test images along with their true labels and the model’s predicted labels. This helps in understanding the model's predictions and areas where it may have misclassified.
5. Image Prediction: An additional functionality is provided where the model can predict the label of a custom image loaded by the user. The image is preprocessed and passed through the model, and the predicted label is displayed.
This project serves as a comprehensive guide for beginners to understand the fundamentals of image classification using CNNs and how to work with the CIFAR-10 dataset.
