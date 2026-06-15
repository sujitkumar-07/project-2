# Handwritten Digit Recognizer - CNN with MNIST Dataset

This project trains a Convolutional Neural Network (CNN) to recognize handwritten digits using the famous MNIST dataset. It's an excellent resource for learning about image processing, neural networks, and deep learning fundamentals.

## Project Overview

The project demonstrates:
- Image preprocessing and normalization
- CNN architecture design with convolutional and pooling layers
- Model training and validation
- Performance evaluation with various metrics
- Prediction and visualization of results

## Dataset

- **MNIST (Modified National Institute of Standards and Technology)**: 70,000 images of handwritten digits (0-9)
  - 60,000 training images
  - 10,000 test images
  - 28×28 pixel grayscale images
  - 10 classes (digits 0-9)

## Requirements

Install dependencies using:
```bash
pip install -r requirements.txt
```

Key libraries:
- **TensorFlow/Keras**: Deep learning framework
- **NumPy**: Numerical computations
- **Matplotlib**: Visualization
- **scikit-learn**: Additional metrics and utilities

## Project Structure

```
project2/
├── handwritten_digit_recognizer.ipynb  # Main Jupyter notebook
├── requirements.txt                     # Python dependencies
└── README.md                           # This file
```

## Quick Start

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Launch Jupyter**:
   ```bash
   jupyter notebook
   ```

3. **Open and run the notebook**:
   - Open `handwritten_digit_recognizer.ipynb`
   - Run cells sequentially to train and evaluate the model

## Notebook Sections

1. **Import Required Libraries** - Load TensorFlow, Keras, NumPy, Matplotlib, and scikit-learn
2. **Load and Explore the MNIST Dataset** - Understand data structure and visualize samples
3. **Preprocess the Data** - Normalize and prepare data for training
4. **Build the CNN Model** - Design the neural network architecture
5. **Compile the Model** - Configure optimizer and loss function
6. **Train the Model** - Train on MNIST training data
7. **Evaluate Model Performance** - Test on unseen data and calculate metrics
8. **Make Predictions on New Digits** - Classify custom handwritten digits
9. **Visualize Results** - Plot predictions, confusion matrix, and training history

## Model Architecture

The CNN typically includes:
- **Convolutional Layers**: Extract features from images
- **Pooling Layers**: Reduce spatial dimensions
- **Dropout Layers**: Prevent overfitting
- **Dense (Fully Connected) Layers**: Classification
- **Output Layer**: 10 units for digit classification

## Expected Performance

A well-trained CNN on MNIST typically achieves:
- **Training Accuracy**: > 99%
- **Test Accuracy**: > 98%

## Learning Outcomes

By working through this project, you'll learn:
- How CNNs extract spatial features from images
- Image preprocessing techniques
- Model training and validation strategies
- Hyperparameter tuning
- Model evaluation and performance metrics
- How to visualize and interpret model predictions

## Future Enhancements

- Experiment with different CNN architectures
- Apply data augmentation techniques
- Use transfer learning with pre-trained models
- Deploy the model as a web service
- Test on handwritten digits from other datasets (SVHN, etc.)

## References

- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [TensorFlow/Keras Documentation](https://www.tensorflow.org/)
- [CNN Fundamentals](https://en.wikipedia.org/wiki/Convolutional_neural_network)
