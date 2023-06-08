# Airbnb Listing Price Prediction

This project aims to predict the listing price range for Airbnb listings in Montreal. The goal is to provide new hosts with a recommended pricing range based on the characteristics of their listing. By using machine learning techniques, we can optimize the user experience and make it easier for new hosts to set competitive prices for their listings.

## Features

- Text Inputs: The model considers textual information such as the listing title, description, and neighborhood to predict the price range.
- Image Inputs: The model analyzes images of the listing to extract visual features that contribute to the price prediction.
- Multi-Modality Learning: By combining text and image inputs, the model leverages multi-modality learning to enhance the prediction accuracy.
- Multi-Objective Learning: The model predicts both the price range and the listing type, enabling multi-objective learning to provide more comprehensive recommendations.

## Dataset

The dataset used for training and evaluation contains Airbnb listings from various areas in Montreal during 2019. It provides rich information for each listing, including links to thumbnails and other relevant details. The dataset undergoes preprocessing to prepare the inputs for the machine learning model.

## Tasks and Approach

1. Data preprocessing: The dataset is preprocessed to extract relevant features from the text and image inputs. Textual data is cleaned, tokenized, and transformed into numerical representations. Images are processed using computer vision techniques to extract meaningful visual features.
2. Model development: The model architecture includes GRU/LSTM layers for sequential text data, Conv2d layers for image data, and multi-modality learning techniques to combine both modalities. The model is trained using multi-objective learning to predict price range and listing type simultaneously.
3. Hyperparameter tuning: Different hyperparameters and configurations are explored using the data science life-cycle. Trial iterations are performed, documenting the reasoning behind each change and the expected outcome. Hyperparameter search methods such as grid search, random search, and Bayesian search are utilized.
4. Evaluation and optimization: The model's performance is evaluated using the public leaderboard. Observations and thoughts from each trial iteration are documented to guide further improvements. Techniques to address underfitting and overfitting are applied to optimize the model.
5. Transfer learning and up-training (bonus): Additional steps may include transfer learning and up-training techniques to further enhance the model's performance and generalize its predictions.

