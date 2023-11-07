# Dataset and Code
[PAKDD'24] A Hierarchical Topic Modeling Analysis of COVID-19 Vaccine Mentions on Korean Twitter Posts

Our analysis is performed in the following steps:
1. Collecting korean twitter mentioning covid-19 vaccine('Astrazeneca, Janssen, Novavax, Moderna, Pfizer)
2. Preprocessing collected data
   - Data cleansing
   - Synonym unification
   - Sentence correction
   - Stopwords Building using API
3. HTM model comparison & selection
   - Models : CluHTM, BERTopic, hLDA  
   - 5 Iterations
   - Sampling data at 0.1x
   - Compute an HCSD(Hierarchical Complex of Similarity and Diversity) score
   - Compute the average HCSD score per model
4. Analysis of discourse
   - Generate the title of topics using the GPT-3 model
   - Generate WordsCloud
   - Interpretation of a produced hierarchical topic model
