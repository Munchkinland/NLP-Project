# URL Spam Detection Project 🔍

![_0e30262b-32f3-4494-be98-0a732f5293ce](https://github.com/Munchkinland/NLP-Project/assets/92251234/9a85c6e9-7863-48b0-9fee-5fceda25a1ac)

# Description 📝

This project implements a machine learning model for URL spam detection. It uses Natural Language Processing (NLP) techniques and a Support Vector Machine (SVM) to classify URLs as spam or not spam.

# Installation 💻

To install the necessary dependencies, clone the repository and run the following command in your local environment:

pip install -r requirements.txt

### Requirements
- Python 3.6+
- Libraries: pandas, regex, nltk, scikit-learn (included in requirements.txt)

# Usage 🚀

Follow these steps to run the project:

- **Data Preprocessing**: Load and clean data to remove duplicates and unwanted characters.
- **Text Processing**: Apply lemmatization and stopword removal to the URL texts.
- **Feature Extraction**: Use TF-IDF to convert the text into a numerical format suitable for the model.
- **Model Training**: The SVM model is trained with the processed data.
- **Hyperparameter Optimization**: Use GridSearchCV to find the best hyperparameters for the SVM model.
- **Model Evaluation**: Evaluate the accuracy of the model before and after optimization.

### Running Scripts
To run the main script, use the following command:

python app.py

markdown
Copy code

# Contribution 🤝

Contributions are welcome. If you want to contribute to the project, please:

- Fork the repository.
- Create a branch for your feature (`git checkout -b feature/fooBar`).
- Make your changes and commit them (`git commit -am 'Add some fooBar'`).
- Push your branch (`git push origin feature/fooBar`).
- Create a new Pull Request.

# License 📜

This project is licensed under the MIT License - see the LICENSE.md file fo
