# CIFAR-10 Image Classifier
## By Aman Brar

### Overview and Purpose
In this project, I have developed multiple convolutional neural networks (CNNs) to classify images from the CIFAR-10 dataset, which includes 60,000 images distributed across 10 different classes. The goal was to incrementally enhance CNN architectures to improve classification accuracy, a foundational skill for applications in various advanced fields such as autonomous driving and medical diagnostics.

### Data Exploration
I began by exploring the dataset, which consists of 50,000 training images and 10,000 testing images, ensuring uniform distribution across the classes. This was an essential step to understand the data and confirm its structure, which underpins the training process of machine learning models.

### Model Building and Training
Four neural network models were constructed, starting from a simple baseline model to more complex iterations:
- The `base` model: A linear classifier with a single layer.
- The `first_iteration` model: Includes an additional hidden layer for complexity.
- The `second_iteration` model: Introduces convolutional and pooling layers.
- The `third_iteration` model: Expands further with two convolutional layers and multiple fully connected layers.

Each model was trained using the CrossEntropyLoss and optimized with the Adam optimizer, across 10 epochs with accuracies computed for both training and test sets.

### Conclusion and Results
The project findings were clear and promising: increasing model complexity correlated with higher accuracy. The `third_iteration` model outperformed others with a test accuracy peak at 0.7180, highlighting the potential of deeper networks. Future work will focus on methods like data augmentation and hyperparameter optimization to further enhance performance.
