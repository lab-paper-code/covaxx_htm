# Dataset and Code
[EDBT'25] Hierarchical Topic Modeling Analysis of COVID-19 Vaccine Tweets

Our analysis is performed in the following steps:
1. Collecting korean twitter mentioning covid-19 vaccine(Astrazeneca, Janssen, Novavax, Moderna, Pfizer)
2. Preprocessing collected data
   - Data cleansing
   - Synonym unification
   - Sentence correction
   - Stopwords Building using API
3. HTM model comparison & selection
   - Models : CluHTM, BERTopic, hLDA  
   - Compute the HHI(Hierarchical Harmony Index) score
   - Compute the HHI score per model
4. Analysis of discourse
   - Interpretation of a produced hierarchical topic model
