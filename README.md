# Spam Email Classification

## Project Overview
This project focuses on detecting spam emails using machine learning techniques. The system is designed to classify emails as either spam or ham based on their content, sender information, and other relevant attributes. The goal is to enhance email security by filtering out malicious or irrelevant messages, thereby improving communication efficiency.

## Goal
The primary objective of this project is to develop an accurate and efficient spam classification model. Specifically, we aim to:
- Utilize Natural Language Processing (NLP) and machine learning techniques to classify emails.
- Implement a robust pipeline for preprocessing email text data.
- Train and evaluate different classification models to achieve high accuracy and low false positive/negative rates.
- Deploy the model in a FastAPI server to allow real-time classification of emails.

## Approach
1. **Data Preprocessing**
   - Tokenization and text cleaning.
   - Removing stop words and punctuation.
   - Feature extraction using TF-IDF and word embeddings.
2. **Model Selection & Training**
   - Implementing classifiers such as Naive Bayes, Logistic Regression, and Random Forest.
   - Evaluating models using confusion matrices, accuracy, precision, recall, and F1-score.
3. **Deployment**
   - Setting up a FastAPI endpoint for real-time classification.
   - Integrating the model into an email processing pipeline.

## Results
- The best-performing model achieved an accuracy of **99%** with a precision.

## Future Improvements
- Enhance feature extraction with deep learning techniques (e.g., LSTMs or Transformers).
- Improve classification using ensemble methods.
- Integrate the model with real email platforms for live testing.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/spam-email-classification.git
   cd spam-email-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook for model training:
   ```bash
   jupyter notebook Spam_email_classification.ipynb
   ```
4. Start the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

## License
This project is open-source and available under the MIT License.

## Contributors
- Brian Ong

For any inquiries or contributions, feel free to reach out!

