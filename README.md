🎭 Sentiment Analysis Project

A machine learning-based sentiment analysis tool that classifies movie reviews as positive or negative using a Naïve Bayes classifier.

✨ Features

📊 Generates and processes a labeled movie review dataset

📝 Uses CountVectorizer for text preprocessing

🤖 Trains a MultinomialNB model for sentiment classification

📈 Evaluates model performance with accuracy metrics and classification reports

🔍 Provides a function for custom sentiment predictions

🔧 Installation

Clone the repository, navigate to the project directory, and install dependencies.

🚀 Usage

Generate the dataset, train the model, and predict sentiment for custom reviews.

📦 Dependencies

🐍 Python 3.x

🐼 Pandas

📚 Scikit-learn

🔢 NumPy

📊 Sample Output

After training the model, the expected output will include accuracy and a classification report:

Accuracy: 0.85

Classification Report:
              precision    recall  f1-score   support

           0       0.84      0.86      0.85       100
           1       0.86      0.84      0.85       100

    accuracy                           0.85       200
   macro avg       0.85      0.85      0.85       200
weighted avg       0.85      0.85      0.85       200

To predict a custom sentiment:

from test import predict_sentiment
print(predict_sentiment("This movie was fantastic!"))

Expected Output:

Positive

🤝 Contribution

Fork the repository, make improvements, and submit a pull request.

📜 License

Licensed under the MIT License.
