# NLP Topic Modeling Project  

This project aims to extract and analyze topics from Eenadu news articles using Natural Language Processing (NLP) techniques. The pipeline includes web scraping, preprocessing, topic modeling, and result visualization.

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

### **Tools and Their Importance**

1.  **Indic NLP Library**

    -   **Purpose**: A library designed specifically for processing Indic languages like Telugu.
    -   **Importance**:
        -   Provides support for tokenization, transliteration, and text normalization for Telugu scripts.
        -   Handles the unique grammar and structure of Telugu, enabling accurate preprocessing.
        -   Essential for building NLP pipelines for non-Latin scripts.
2.  **Stanza**

    -   **Purpose**: A multi-language NLP library by Stanford for text analysis.
    -   **Importance**:
        -   Provides tools for tokenization, part-of-speech tagging, and dependency parsing.
        -   Supports Telugu, making it an essential tool for deeper linguistic analysis.
        -   Facilitates advanced NLP tasks, ensuring high-quality text preparation.
3.  **Gensim**

    -   **Purpose**: A Python library for topic modeling and document similarity analysis.
    -   **Importance**:
        -   Implements the **Latent Dirichlet Allocation (LDA)** algorithm for topic modeling.
        -   Provides efficient methods to process large datasets using a streaming API.
        -   Includes coherence score calculation to evaluate topic model quality.
4.  **PyLDAvis**

    -   **Purpose**: A library for interactive topic modeling visualization.
    -   **Importance**:
        -   Helps visualize and interpret the results of LDA models.
        -   Provides an intuitive interface to explore relationships between topics, words, and documents.
        -   A key tool for presenting insights in a visually compelling format.
5.  **TF-IDF (via Gensim or custom implementation)**

    -   **Purpose**: A statistical measure to evaluate the importance of words in documents.
    -   **Importance**:
        -   Prepares the text for LDA by highlighting important words while filtering out less relevant ones.
        -   Reduces noise in the data, improving the quality of the topic modeling.
