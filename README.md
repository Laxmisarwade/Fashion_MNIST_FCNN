# Fashion MNIST Classification using Fully Connected Neural Network (FCNN)

## About the Project
This project is part of Module 4: Introduction to Fully Connected Neural Networks from the Intellipaat Artificial Intelligence Certification Course.

The main aim of this project is to classify fashion images into 10 different categories using a Fully Connected Neural Network (FCNN).

## Dataset
The Fashion MNIST dataset contains grayscale images of fashion items.

- Training images: 60,000
- Testing images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Matplotlib
- Seaborn
- TensorFlow / Keras

## Project Steps
1. Imported the required libraries.
2. Loaded the Fashion MNIST dataset.
3. Visualized sample images and class distribution.
4. Normalized pixel values between 0 and 1.
5. Converted labels into one-hot encoding.
6. Built a Fully Connected Neural Network.
7. Compiled the model using SGD optimizer and categorical cross-entropy loss.
8. Trained the model using a validation split.
9. Evaluated the model's performance.
10. Visualized training and validation accuracy and loss.

## Model Architecture
The neural network consists of:

- Flatten layer to convert images into a one-dimensional array.
- Dense layer with 128 neurons and ReLU activation.
- Dense layer with 64 neurons and ReLU activation.
- Output layer with 10 neurons and Softmax activation.

## Fashion Categories
The model classifies images into the following categories:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## How to Run the Project
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install tensorflow numpy matplotlib seaborn
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Fashion_MNIST_FCNN.ipynb`.
5. Run all cells from top to bottom.

## Results
The model is evaluated using accuracy and loss. Training and validation graphs are plotted to understand the learning performance and identify possible overfitting or underfitting.

The final test accuracy and loss can be added here after running the notebook.

## Learning Outcomes
- Understood the basics of a Fully Connected Neural Network.
- Learned image preprocessing and normalization.
- Learned one-hot encoding.
- Built and trained a neural network using TensorFlow/Keras.
- Evaluated model performance using accuracy and loss graphs.

## Author
Laxmi Bhairavnath Sarwade

## Acknowledgement
This project was completed as part of the Intellipaat Artificial Intelligence Certification Course.

