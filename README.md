# DeepFake Detection System

This project is a deepfake detection system developed using EfficientNet B4 CNN and Streamlit to detect manipulated images and videos. The system aims to enhance digital security by identifying fake media, addressing the growing concerns around multimedia authenticity.

## Features

- **EfficientNet B4 Model**: A deep convolutional neural network for detecting deepfake content by effectively extracting and classifying features.
- **User Interface with Streamlit**: A clean and simple web interface for uploading and processing images for deepfake detection.
- **Visual Indication**: Real-time feedback with clear labels marking the media as real or fake, alongside probability scores.

## Tools & Technologies Used

- **Python**: Backend programming.
- **TensorFlow**: For implementing the EfficientNet B4 model.
- **EfficientNet B4**: Convolutional Neural Network architecture for deepfake detection.
- **Sklearn**: For model evaluation and utility functions.
- **NumPy & Pandas**: Libraries for efficient data processing.
- **Streamlit**: Frontend library for building an interactive web application.

## How It Works

1. **Upload an Image**: Users upload an image in supported formats (JPG, PNG, JPEG).
2. **Processing**: The image is processed through the EfficientNet B4 model, which extracts features and classifies whether the image is real or fake.
3. **Results**: The app outputs the classification result with a label (real or fake) and the model's probability score.

## Limitations

- **Variations in Image Quality**: Image quality, lighting, and facial expressions can affect the model's performance.
- **Emerging Deepfake Techniques**: The model may not fully detect the latest deepfake techniques using more advanced methods.
- **Dataset Dependence**: The accuracy of the model relies heavily on the quality and diversity of the training dataset.

## Setup and Installation

1. **Clone the repository**:
   ```bash
     git clone https://github.com/username/deepfake-detector.git
2.**Install dependencies**:
    pip install -r requirements.txt
3.**Run the Streamlit app**:
    streamlit run app.py
