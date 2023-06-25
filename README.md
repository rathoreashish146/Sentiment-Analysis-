# Sentiment Analysis System

## Introduction
This project aims to develop a sentiment analysis system that predicts the sentiment (positive, negative, or neutral) of upcoming movie reviews. The system utilizes text vectorization techniques and the IMDB 50k Movie Dataset from Kaggle to train a machine learning model.

## Features
- Predicts the sentiment of movie reviews as either positive, negative, or neutral.
- Utilizes text vectorization techniques to convert textual data into numerical representations.
- Trains the sentiment analysis model using Support Vector Machines (SVM), a popular supervised learning algorithm.
- The IMDB 50k Movie Dataset from Kaggle is used for training and evaluation purposes.
- Technologies used: Supervised Learning, Sklearn, Pandas, NumPy, Python.

## Installation
1. Clone this repository: `git clone <repository_url>`
2. Install the required dependencies by running: `pip install -r requirements.txt`
3. Download the IMDB 50k Movie Dataset from Kaggle and place it in the designated data folder.
4. Run the main application script: `python sentiment_analysis.py`

## Usage
1. Ensure that the dataset is properly loaded and preprocessed by running the data preprocessing script: `python data_preprocessing.py`.
2. Train the sentiment analysis model by executing the training script: `python train_model.py`.
3. Once the model is trained, the main application script can be used to predict the sentiment of upcoming movie reviews: `python sentiment_analysis.py`.

## Contributing
Contributions to this project are welcome. To contribute, please follow these steps:
1. Fork this repository.
2. Create a new branch: `git checkout -b my-new-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request detailing your changes.

## License
This project is licensed under the [MIT License](LICENSE).
