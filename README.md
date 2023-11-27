# PredictionsDL
## Deep Prediction Hub

# Deep Prediction Hub Overview

Welcome to Deep Prediction Hub, a web application powered by Streamlit that offers two powerful deep learning tasks: Sentiment Classification and Tumor Detection.

## Tasks

1. **Sentiment Classification**
   - Classify the sentiment of a given text as either "Positive" or "Negative."
   - Input a review, and the application utilizes various models to provide sentiment classification.

2. **Tumor Detection**
   - Detect the presence of a tumor in medical images.
   - Users can upload an image, and the application employs a Convolutional Neural Network (CNN) model for tumor detection.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Required packages: streamlit, numpy, cv2, PIL, tensorflow
- Pre-trained models: PP.pkl, BP.pkl, DP.keras, RN.keras, LS.keras, CN.keras
- Trained IMDb word index: Ensure the IMDb word index is available for sentiment classification.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/deep-prediction-hub.git
   ```

### Usage

- Access the application by opening the provided URL after running the Streamlit app.
- Choose between "Sentiment Classification" and "Tumor Detection" tasks.

#### Sentiment Classification

1. Enter a review in the text area.
2. Select a model from the dropdown.
3. Click "Submit" and then "Classify Sentiment."

#### Tumor Detection

1. Upload an image using the file uploader.
2. Click "Detect Tumor" to perform tumor detection.

## Models

- **Perceptron (PP.pkl):** Perceptron-based sentiment classification model.
- **Backpropagation (BP.pkl):** Backpropagation-based sentiment classification model.
- **DNN (DP.keras):** Deep Neural Network sentiment classification model.
- **RNN (RN.keras):** Recurrent Neural Network sentiment classification model.
- **LSTM (LS.keras):** Long Short-Term Memory sentiment classification model.
- **CNN (CN.keras):** Convolutional Neural Network tumor detection model.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Please follow the contribution guidelines.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
