# Twitter-Based Sentiment Analysis for Brand Perception

This project performs sentiment analysis on Twitter data to understand brand perception. It uses Natural Language Processing (NLP) techniques to analyze social media content and classify sentiments as Positive, Negative, or Neutral.

## Overview
The notebook `NLP_TWITTER_ANALYSIS.ipynb` contains a comprehensive analysis including:
- Data exploration and preprocessing
- Sentiment analysis using VADER
- Text preprocessing (tokenization, lemmatization, stopword removal)
- Visualization of sentiments and word clouds
- Machine learning model training for sentiment classification using Logistic Regression
- Evaluation of the model performance

## Features
- Sentiment analysis on Twitter data
- Data visualization (plots, word clouds)
- Text preprocessing pipeline
- Machine learning classification model
- Performance metrics and evaluation

## Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required Python packages (see Installation)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/parthparmar07/SocialMedia_NLP_Analysis.git
   cd SocialMedia_NLP_Analysis
   ```

2. Install the required packages:
   ```bash
   pip install matplotlib seaborn numpy nltk wordcloud scikit-learn pandas
   ```

3. Download NLTK data (if not already downloaded):
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('wordnet')
   ```

## Usage

1. Ensure you have the dataset file `twitter data.csv` in the project directory.

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook NLP_TWITTER_ANALYSIS.ipynb
   ```

3. Run the cells in order to perform the analysis.

## Data
The dataset should be a CSV file named `twitter data.csv` with the following columns:
- `ID`: Unique identifier for each entry
- `Entity`: Entity or brand mentioned
- `Sentiment`: Sentiment labels (Positive, Negative, Neutral)
- `Content`: Text content of the tweets

Note: The dataset is not included in this repository due to size or privacy concerns. You need to obtain or generate the dataset separately.

## Results
The analysis provides:
- Sentiment distribution visualizations
- Word clouds for positive and negative sentiments
- Model accuracy and classification reports
- Insights into brand perception based on social media data

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is open source. Please check the license file for details.
