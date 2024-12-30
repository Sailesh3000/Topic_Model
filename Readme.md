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

   ## Run the Scripts  

### `web_scraping_eenadu.ipynb`  
- Contains the web scraping code to extract data from Eenadu news articles.  
- Run this notebook to scrape and save the dataset.  

### `data_preprocessing.ipynb`  
- Handles the entire preprocessing workflow and includes topic modeling steps.  
- Upload the dataset generated from the web scraper or provide your dataset in the appropriate format.  

