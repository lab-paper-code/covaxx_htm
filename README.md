# Dataset and Code
[CIKM'24] HARIN: A Novel Metric for Hierarchical Topic Model Assessment

Our analysis is performed in the following steps:
1. Dataset Collection:
    - private: korean twitter mentioning covid-19 vaccine(Astrazeneca, Janssen, Novavax, Moderna, Pfizer)
    - public:
      - BBC: http://mlg.ucd.ie/datasets/bbc.html
         
2. Preprocessing collected data
   - Data cleansing
   - Synonym unification
   - Sentence correction
   - Stopwords Building using API
     
3. HTM model comparison & selection
   - Models : BERTopic, CluHTM, hLDA, and HyHTM  
   - Compute the HARIN (**H**ier**A**rchical ha**R**mony **IN**dex) score
   - Compute the HARIN score per model
     
4. Comparing HARIN with Human Judgment 
   - Conduct surveys to derive human scores(questionaire.zip)
