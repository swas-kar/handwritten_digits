# handwritten_digits
This project uses TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. The model is trained using a neural network with different configurations to achieve higher accuracy.

## Deployment

To deploy this project run:

1.Clone the repository:

```bash
  git clone https://github.com/your_username/handwritten-digits-recognition.git
```
2.Install the required dependencies:
```bash
  git clone https://github.com/your_username/handwritten-digits-recognition.git
```
3.Run the Jupyter notebook or Python script to train the model and test it on the MNIST dataset.


## Features

### Dataset
The MNIST dataset is used for training and testing the model. It consists of 60,000 training images and 10,000 testing images of handwritten digits from 0 to 9.

### Model Architecture
The model consists of a single dense layer with 10 units (one for each digit) and uses the 'sigmoid' activation function.

### Training and Evaluation
The model is trained using the 'adam' optimizer and 'sparse_categorical_crossentropy' loss function. After training for 5 epochs, the model achieves an accuracy of around 92.48% on the test dataset.

### Results
The model is able to correctly predict the digits from the test dataset with high accuracy(upto 97%). A confusion matrix is used to visualize the performance of the model.
