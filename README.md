# Dataset and Code
[WSDM'24] A Hierarchical Topic Modeling Analysis of COVID-19 Vaccine Mentions on Korean Twitter Posts

Our analysis is followed below steps:
1. Collecting korean twitter mentioning covid-19 vaccine('Astrazeneca, Janssen, Novavax, Moderna, Pfizer)
2. Preprocessing collected data
   - Data cleaning
   - Synonym unification
   - Sentence correction
   - Stopwords Building using API
3. HTM model comparision & selection
   - Models : CluHTM, BERTopic, hLDA  
   - 5 Iteration
   - Sampling data at 0.1x
   - Compute HCSD(Hierarchical Complex of Similarity and Diversity) score
   - Compute average HCSD score per model
4. Analysis of discourse
   - Generate title of topics using GPT-3 model
   - Generate WordsCloud
   - Interpretation of hierarchical topic model
