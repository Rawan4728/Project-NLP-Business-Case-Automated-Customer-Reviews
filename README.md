# Project-NLP-Business-Case-Automated-Customer-Reviews


## Project Overview
This project aims to develop a product review system powered by Natural Language Processing (NLP) models that aggregate customer feedback from different sources. The key tasks include:

- **Classifying reviews** into positive, negative, or neutral sentiment.
- **Clustering product categories** into meta-categories for better insights.
- **Using generative AI** to summarize reviews and create recommendation articles based on aggregated data.

## Datasets
The project uses the following datasets from Hugging Face:

- `Datafiniti_Amazon_Consumer_Reviews_of_Amazon_Products.csv`
- `Datafiniti_Amazon_Consumer_Reviews_of_Amazon_Products_May19.csv`

These datasets provide detailed consumer reviews for a variety of products.

## Model Development
For classifying customer reviews into positive, negative, or neutral sentiment, we leverage pretrained transformer-based models to take advantage of powerful language representations without having to train models from scratch.

The following models were used:
- **bert-base-uncased**: A version of BERT that has been pretrained on a large corpus of English text.
- **roberta-base**: A robustly optimized version of BERT that has shown superior performance in NLP tasks.

## Key Features
- **Review Classification**: Classifying customer reviews into positive, negative, and neutral categories.
- **Product Clustering**: Grouping products into 4-6 meta-categories based on review content.
- **Review Summarization**: Using generative AI to summarize reviews into comprehensive recommendation articles, highlighting top-rated products, key complaints, and providing product comparisons.

## References
Streamlit and saved model: [Google Drive Link](https://drive.google.com/drive/folders/18Hic-mTfUUsgdRbx2AYnnCp3OHchAyKP?usp=drive_link)

bert-base-uncased: A version of BERT that has been pretrained on a large corpus of English text.

roberta-base: A robustly optimized version of BERT that has shown superior performance in NLP tasks.



