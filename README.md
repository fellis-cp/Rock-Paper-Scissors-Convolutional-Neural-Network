
# Rock Paper Scissors Convolutional Neural network


This project involves training a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify Rock-Paper-Scissors hand gestures from images.


## Dataset

  https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip\

## Documentation

1. Data Collection:
- Downloaded the dataset and extracted the images using Python's zipfile library.

2. Data Preprocessing:

- Images were resized to 150x150 pixels to standardize the inputsize for the CNN.
- Augmented the dataset using ImageDataGenerator from TensorFlow to increase variation in the training set.

3. Model Architecture:
 - Designed a CNN architecture consisting of Conv2D, MaxPooling2D, Flatten, Dropout, and Dense layers.
- The final layer utilizes softmax activation for multi-class classification

4. Model Training:

- Trained the model using the prepared training and validation datasets.
- Used callbacks for early stopping if validation accuracy surpassed 95% to prevent overfitting.

5. Model Evaluation:
- Plotted training and validation accuracy/loss to visualize model performance.
- Achieved an accuracy of [your accuracy value]% on the validation set after [number of epochs] epochs.

6. Prediction:

- Utilized the trained model to predict new Rock-Paper-Scissors images.
- Uploaded images using Google Colab and predicted the corresponding hand gesture.






## Deployment

```bash
Clone the repository and follow the steps provided in the Jupyter Notebook (Untitled8.ipynb) to reproduce the experiment.
```

```bash
Use the provided trained model for predictions or further analysis.
```

