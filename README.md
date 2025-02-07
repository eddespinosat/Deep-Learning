# Deep-Learning

### 1. Effect deep generalization
The first program trains simple neural networks on the MNIST dataset to analyze how the hidden layer size affects the model's ability to generalize to new data. It uses various hidden layer sizes, evaluates performance on validation and test sets, and compares losses and accuracies based on the number of parameters. Finally, it visualizes the results in graphs.

---

### 2. Complexity Graphs
The second program works with the **German Credit Risk** dataset, implementing a neural network for binary classification (good/bad credit). It explores the impact of training set size and hidden layer size on training errors (\(E_{in}\)) and test errors (\(E_{out}\)). It performs repeated experiments, calculates error statistics, and shows graphs that relate errors to data size and model complexity.

---

### 3. CNN Classification on Fashion MNIST
This program uses PyTorch to train a **custom convolutional neural network (CNN)** on the **Fashion MNIST** dataset. It includes:

- **Data preparation**: utilizes `DataLoader` to load images as tensors.
- **CNN model**: three convolutional blocks with ReLU, MaxPooling, and a dense layer for classification into 10 classes.
- **Training**: optimization with Adam, cross-entropy loss, and accuracy (`Accuracy` from TorchMetrics), with an **early stopping** mechanism.
- **Results**: achieved **92% test accuracy** and **94% training accuracy** after 12 epochs, with a low test loss (0.249), indicating effective training and minimal overfitting.
- **Visualization**: displays prediction errors with true and predicted labels for analysis.

This demonstrates a solid application of CNNs for image classification.
