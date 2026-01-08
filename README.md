MNIST Digit Classifier --> CNN

A Convolutional Neural Network built with PyTorch for digit recognition,for a 98.77% accuracy on the MNIST dataset.

 Results
- Test Accuracy: 98.77%
- Training Time: 2.8 minutes (GPU)
- Epochs: 5

Model Architecture
Conv2D (1→6 channels, 3x3): ReLU: MaxPool(2x2)-->
Conv2D (6→16 channels, 3x3): ReLU: MaxPool(2x2)-->
Flatten-->
Fully Connected (400→120): ReLU-->
Fully Connected (120→84): ReLU-->
Fully Connected (84→10): LogSoftmax-->


 Dataset
- Training samples: 60,000
- Test samples: 10,000
- Image size: 28x28 grayscale
- Classes: 10 (digits 0-9)

 Technologies
- PyTorch
- torchvision (MNIST dataset)
- NumPy
- Pandas
- Matplotlib
