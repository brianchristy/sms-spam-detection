# SMS Spam Detection Model

A machine learning-based web application that detects whether an SMS message is spam or not spam using Natural Language Processing (NLP) techniques.

## Features

- Real-time spam detection for SMS messages
- User-friendly web interface built with Streamlit
- Text preprocessing using NLTK
- Support for multi-line text input
- Instant prediction results

## Technologies Used

- Python
- Streamlit
- NLTK (Natural Language Toolkit)
- Machine Learning (using a pre-trained model)
- Pickle for model serialization

## Prerequisites

- Python 3.x
- Required Python packages:
  - streamlit
  - nltk
  - scikit-learn
  - pickle

## Installation

1. Clone this repository:
```bash
git clone https://github.com/brianchristy/sms-spam-detection
cd spam-detection
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Download required NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Usage

1. Run the Streamlit app:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the URL shown in the terminal (typically http://localhost:8501)

3. Enter the SMS message in the text area

4. Click the "Predict" button to get the result

5. The model will classify the message as either "Spam" or "Not Spam"

## Model Details

The application uses:
- Text preprocessing (lowercase conversion, tokenization, stopword removal, stemming)
- TF-IDF vectorization for text feature extraction
- A pre-trained machine learning model for classification

## Author

Brian C.

## License

This project is licensed under the MIT License. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.