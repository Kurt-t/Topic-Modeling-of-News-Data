# Topic-Modeling-of-News-Data
## Data Source:
The data are English news articles crawled from multiple news media websites. Requests and Selenium are the main tools to conduct web scraping.  
1. Articles concerning "climate change" from Global Times  
2. News articles from New York Times published during December, 2019
## Preprocessing:
Multiple settings were tested, including stemming, lemmatizing, introducing bigrams and trigrams, etc.
## Models:
1. LDA: the Latent Dirichlet Allocation Model  
2. NMF: Non-negative Matrix Factorization Model  The LDA model on the NYT data was trained and tuned to get optimal result based on coherence score.
