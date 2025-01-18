# Sentiment Analysis Notebook

## Overview
This Jupyter Notebook provides a step-by-step guide to performing sentiment analysis on customer reviews. It covers tasks such as loading the dataset, cleaning and preprocessing the reviews, tokenizing the text, exploring tokens and product categories, extracting adjectives, and determining the sentiment of each review.

## Tasks Covered

### Loading the Dataset
- Load a dataset containing customer reviews and product categories.

### Cleaning and Preprocessing
- Convert reviews to lowercase and remove punctuation.

### Tokenization and Stop Word Removal
- Tokenize the reviews and remove common stop words.

### Exploring Tokens and Product Categories
- Analyze the frequency of tokens and the distribution of reviews across product categories.

### Extracting Adjectives
- Extract adjectives from the reviews to understand descriptive language.

### Sentiment Analysis
- Use the VADER sentiment analysis tool to determine the sentiment of each review.

## Dependencies
Make sure you have the following Python libraries installed:

```bash
pip install pandas nltk wordcloud plotly matplotlib
```

Download the required NLTK datasets by running:

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('vader_lexicon')
```

## Usage

### Install Dependencies
Install the required libraries using pip:

```bash
pip install pandas nltk wordcloud plotly matplotlib
```

### Download NLTK Datasets
Run the following commands in a Python environment to download the necessary NLTK datasets:

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('vader_lexicon')
```

### Run the Notebook
Open the Jupyter Notebook and execute each cell sequentially to perform the sentiment analysis.

## Dataset
The dataset used in this notebook is a CSV file containing customer reviews and their corresponding product categories. It is loaded using the pandas library.

## Results
The notebook provides insights into the sentiment of customer reviews by analyzing token frequencies, extracting adjectives, and determining sentiment using the VADER sentiment analyzer. Results are visualized using word clouds and frequency distribution plots.

## Contributing
Contributions are welcome! Fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- **NLTK** for natural language processing.
- **VADER** for sentiment analysis.
- **Pandas**, **WordCloud**, **Plotly**, and **Matplotlib** for data manipulation and visualization.
