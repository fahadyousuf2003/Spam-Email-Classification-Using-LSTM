# Spam Email Classification Using Long Sort Term Memory Architecture

## Introduction
This project demonstrates a deep learning-based solution for classifying emails as spam or non-spam using an LSTM (Long Short-Term Memory) neural network. The system retrieves emails from a user's Gmail account, processes the email content, and predicts whether an email is spam or not in real-time.
## Features
### LSTM Neural Network: 
    Utilizes an LSTM-based model to classify emails based on the textual content.
### Automated Email Retrieval: 
    Connects with Gmail via IMAP to automatically fetch emails for classification.
### Real-Time Predictions: 
    Provides real-time predictions on incoming emails, offering practical spam detection.
### Preprocessing: 
    Tokenizes and cleans the email text data for efficient model input.

## How It Works
### Email Retrieval: 
    The project uses imaplib to connect to a Gmail account and retrieve emails.
### Text Preprocessing: 
    Emails are preprocessed to clean and prepare the text data for the model.
### LSTM Classification: 
    The LSTM model classifies each email as spam or non-spam.
### Result Output: 
    The model outputs a prediction for each retrieved email.
    
## Installation
### Prerequisites
    Python 3.7 or above
    Gmail account for testing (IMAP access enabled)
### Required Libraries:
    TensorFlow/Keras
    Numpy
    Pandas
    Matplotlib
    Sklearn
    imaplib
## Steps
- Clone the repository:
git clone https://github.com/fahadyousuf2003/Spam-Email-Classification-Using-LSTM.git
cd Spam-Email-Classification-Using-LSTM

-Install the required packages:
pip install -r requirements.txt

-Enable IMAP for your Gmail account by following this guide.
-Update your Gmail credentials in the config.py file (ensure to use App Password if two-factor authentication is enabled).

Run the notebook script on either Google Colab or Jupyter Notebook:

## How to Use
-After running the script, the program will connect to your Gmail account and retrieve a batch of emails.
-The pre-trained LSTM model will classify each email as spam or non-spam.
-Results will be displayed, and optionally, an image showing the classification can be generated.

## Contribution Guidelines
Feel free to contribute by submitting bug reports, feature requests, or code contributions.

## Contact
For any inquiries or feedback, please contact Fahad Yousuf (fahadyousuf344@gmail.com).
