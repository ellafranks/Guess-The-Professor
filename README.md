***Still in progress***

# Guess-The-Professor

A person's writing style is an example of a behaviour biometric. The words people may use and the way they structure their sentences is distinctive and can often be used to identify the author of a particular work. 

*In this project I aim to compare two economists and classify who is the primary author of an academic paper based on their language.*

To ensure a large corpus, I will use Selenium to scrape Google Scholar, one of the most used academic search engines in the world. 

**Method:**
1. Crawling through Google Scholar and downloading research pdfs using Selenium
2. Parsing and converting pdfs to raw text using Tika 
3. Applying some general rules in order to clean and prepare the text
4. Processing the text using Spacy 
5. Build a classification model to predict if the research paper was Julian Franks or La Porta
6. Explore word embeddings with Word2Vec, FastText and TSNE


