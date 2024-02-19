# SMS-Spam-Detection-with-TensorFlow

## Project Overview

This project aims to classify SMS messages as spam or ham (not spam) using TensorFlow and Python. Inspired by a [GeeksforGeeks tutorial](https://www.geeksforgeeks.org/sms-spam-detection-using-tensorflow-in-python/), this project extends the original work with improvements feature engineering for enhanced performance.

## Enhancements Made

- **Feature Engineering**: Incorporated sentiment analysis as a new feature, hypothesizing that spam messages might exhibit distinct sentiment patterns compared to non-spam messages.

## Dataset

The dataset used for training and testing is the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection), a public collection of labeled SMS messages.

## Requirements

- Python 3.8+
- TensorFlow 2.x
- NLTK
- Pandas
- NumPy

## Usage

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook sms_spam_detection.ipynb`

## Conclusion

In this project, I employed the power of TensorFlow to develop a machine learning model capable of distinguishing spam messages from legitimate ones. Drawing inspiration from foundational tutorials and leveraging the rich capabilities of TensorFlow, I constructed a model that not only understands the textual content of messages but also interprets their underlying sentiment.
