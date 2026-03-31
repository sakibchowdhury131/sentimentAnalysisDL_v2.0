# sentimentAnalysisDL_v2.0

Google Colab notebooks for sentiment analysis of COVID-19 tweets using deep learning. The project preprocesses tweet text (tokenization, stopword removal, stemming) and trains a neural network classifier to categorize tweet sentiment.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sakibchowdhury131/sentimentAnalysisDL_v2.0/blob/main/sentimentAnalysis_test1.ipynb)

## Features

- Loads the [Covid-19 Sentiment Analysis dataset](https://github.com/gitdevqiang/Covid-19-Sentiment-Analysis) from GitHub
- Text preprocessing pipeline: regex cleaning, lowercasing, stopword removal, Porter stemming, `@mention` filtering
- Bag-of-words feature extraction
- Deep learning sentiment classifier trained in Keras/TensorFlow
- Separate preprocessing and training notebooks

## Tech Stack

- Python 3
- Keras / TensorFlow
- NLTK
- NumPy, Pandas
- Google Colab

## Project Structure

| File | Description |
|---|---|
| `sentimentAnalysis_test1.ipynb` | Main notebook: data loading, preprocessing, model training and evaluation |
| `sentimentAnalysis_preprocess.ipynb` | Standalone preprocessing exploration notebook |

## Requirements

```
tensorflow
keras
nltk
numpy
pandas
num2words
```

## Usage

1. Open `sentimentAnalysis_test1.ipynb` in Google Colab.
2. Run all cells — the dataset is cloned automatically from GitHub.

## License

MIT
