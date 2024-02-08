# Dataset and Code
[EDBT'25] HARIN: A Novel Metric for Hierarchical Topic Model Assessment

Our analysis is performed in the following steps:
1. Collecting korean twitter mentioning covid-19 vaccine(Astrazeneca, Janssen, Novavax, Moderna, Pfizer)
2. Preprocessing collected data
   - Data cleansing
   - Synonym unification
   - Sentence correction
   - Stopwords Building using API
3. HTM model comparison & selection
   - Models : BERTopic, CluHTM, hLDA, and HyHTM  
   - Compute the HARIN (**H**ier**A**rchical ha**R**mony **IN**dex) score
   - Compute the HARIN score per model
4. Analysis of discourse
   - Interpretation of a produced hierarchical topic model
