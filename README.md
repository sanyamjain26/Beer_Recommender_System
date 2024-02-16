To assess differences in consumer perceptions across popular beer brands, an analysis of approximately 6000 reviews from a beer review forum was conducted. The objective was to develop a recommendation system that aligns beer brands with consumer preferences.

**Data Preprocessing:** The data was cleaned by excluding brands with fewer than 50 reviews and by removing stopwords from the scraped reviews.

**Exploratory Data Analysis (EDA):** Word frequencies were generated to identify the most discussed beer attributes. Similar attributes were grouped together, and these modifications were applied to the reviews. LIFT analysis was performed to examine the associations between beer brands and specific attributes, as well as to uncover any notable differences among the brands.

**Building the Recommendation System:** Two methodologies were utilized to construct the recommendation system. The first methodology was based on a combination of VADER sentiment analysis and Bag of Words for calculating cosine similarity. The second methodology relied solely on cosine similarity, using word embeddings from Spacy.

Each method has its advantages and disadvantages. Bag of Words (BoW) cosine similarity excels in scenarios where words are uncommon and an exact match is desired. On the other hand, for words that convey more general meanings, utilizing word embeddings to explore a wider spectrum of words offers a more suitable match.
