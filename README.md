# SMS Spam Detection

This project focuses on detecting spam messages using machine learning models. Three models are implemented and compared: **Multinomial Naive Bayes (MultinomialNB)**, **Bidirectional-LSTM**, and **USE-based Transfer Learning**.

## Features
- Preprocesses text data for spam detection.
- Uses advanced machine learning techniques for classification.
- Compares three models to determine the best performance.

## Models Used
1. **MultinomialNB:** A simple yet effective model based on word frequencies.
2. **Bidirectional-LSTM:** A deep learning model capturing sequential dependencies in text.
3. **USE-Transfer Learning:** Leverages the Universal Sentence Encoder for high-quality text embeddings.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/HarshaHharros/SMS-SPAM-CLASSIFIER/tree/main
   cd SMS-SPAM-CLASSIFIER
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook SMS_Spam_Detection_Corrected.ipynb
   ```

## Requirements
Create a `requirements.txt` file with the following contents:

```
tensorflow
tensorflow-hub
numpy
pandas
scikit-learn
jupyter
```

## Open Source
This project is open source and available under the [MIT License](LICENSE). Feel free to contribute, report issues, or suggest features by creating a pull request or opening an issue in the repository.

