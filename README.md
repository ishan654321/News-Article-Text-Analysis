# News-Article-Text-Analysis
This Project is prepared based on news article websites and their body text analysis. I have used BeautifulSoup and NLTK based libraries in python.

The objective of this project is to analyze news article that we find online and answering questions like how a piece of text can be identify into category without knowing the title or actual category. Also, how readability, sentiment and complexity correlated while seeing text of article. We have used various NLP techniques like LDA(latent Dirichlet allocation) and NMF(non negative matrix factorization) with visual understanding. We have used some numerical analysis scores like flesch_reading_ease, flesch_kincaid_grade, smog_index, coleman_liau_index for readability and some topic clusters from methods mentioned above. We successfully completed this project with results and visualizations for better understanding.

There is also use of some widely used simple techniques in NLP as well like n-grams or word cloud or bag of words along with techniques like doc2vec and sbert-kmean clustering and PCA for better 2d plots of topic clusters. Now I will explain some methods of data collections and cleaning along with problems I got while performing this.

- The python file .html is main code of project.
- The news_article1.csv is main csv file we started with.
- The article analysis newspaper is updated csv file with url text of website and scores.
