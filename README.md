 Digit Recognition System

This project is a "Handwritten Digit Recognition System" built using "Deep Learning (CNN)".
It can identify digits (0–9) from images using a trained neural network model.

 Project Overview

The system uses image processing techniques and a "Convolutional Neural Network (CNN)" to classify handwritten digits.
Images are preprocessed and then passed through the model to predict the correct digit.

 Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn

 Dataset

* Custom dataset of digit images (0–9)
* Total images: "200"
* Image size: "24x24 pixels (grayscale)"

 Steps Involved

 1. Data Preprocessing

* Convert images to grayscale
* Resize to 24x24
* Apply thresholding
* Normalize pixel values (0–1)

 2. Model Building (CNN)

* Convolutional Layers (feature extraction)
* MaxPooling Layers (dimensionality reduction)
* Flatten Layer
* Dense Layers (classification)

3. Model Training

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 30

4. Evaluation

* Accuracy
* Loss Graph
* Classification Report (Precision, Recall, F1-score)

 Results

Training Accuracy: ~100%
Testing Accuracy: ~70%

 Note: Lower test accuracy is due to small dataset (overfitting).

 Output

* Loss vs Validation Loss graph
* Predicted vs Actual values
* Classification Report

 How to Run

1. Open the notebook in Google Colab
2. Upload dataset (`DL_Dataset.zip`)
3. Run all cells step-by-step
4. View predictions and results

 Future Improvements

* Use larger dataset (e.g., MNIST)
* Apply Data Augmentation
* Add Dropout layer to reduce overfitting
* Improve model accuracy

 Project File

 `digit_recognition.ipynb`

 Conclusion

This project demonstrates how "Deep Learning + Image Processing" can be used to build a digit recognition system. It provides hands-on understanding of CNN and model evaluation.

 Author
Sakshi Wakchaure


