# Simple-Art-using-LSTM
Create a monochrome image from a prediction using LSTM
This was made during an attempt to use LSTMs for edge prediction.

CODE EXPLANATION
- The code loads a model or creates one and fits it.
- Then it predicts the next pixel repeatedly and creates a new image, which is similar to the original one its given
- The difference between the grayscales of the predicted image and the original image is calculated.
- A threshold is then applied to attempt to detect edges/anomalies thus leading to the artistic view.
