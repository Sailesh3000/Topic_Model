# NLP Topic Modeling Project  

This project aims to extract and analyze topics from Eenadu news articles using Natural Language Processing (NLP) techniques. The pipeline includes web scraping, preprocessing, topic modeling, and result visualization.

---

## Prerequisites  

- Google Colab account  
- Internet access  

---

## How to Run  

1. Open Google Colab:  
   Visit [Google Colab](https://colab.research.google.com/).  

2. Create a new notebook or upload the provided `.ipynb` file.  

3. Install required libraries by running the following commands in a Colab code cell:  
   ```python
   !pip install indic-nlp-library
   !pip install indicnlp
   !pip install gensim
   !pip install pyLDAvis
   !pip install stanza

4.  **Run the Scripts**:

### `web_scraping_eenadu.ipynb`

-   **Purpose**: Automates the extraction of Telugu news articles from the Eenadu website.
-   **Steps**: Run the notebook to collect and save the dataset as a CSV file.

### `topic_modeling.ipynb`

-   **Purpose**: Performs preprocessing steps like normalization, tokenization, stop word removal, stemming, and POS tagging.
-   **Steps**: Upload the dataset generated by the web scraper and preprocess the data for topic modeling.
-   **Purpose**: Implements LDA for topic modeling and evaluates coherence scores for optimal topic selection.
-   **Steps**: Generate topics, calculate coherence scores, and visualize topics using PyLDAvis.
