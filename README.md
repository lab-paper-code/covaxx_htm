# Dataset and Code
[CIKM'24] HARIN: A Novel Metric for Hierarchical Topic Model Assessment

Our analysis is performed in the following steps:
1. Dataset Collection:
    - private: korean twitter mentioning covid-19 vaccine(Astrazeneca, Janssen, Novavax, Moderna, Pfizer)
    - public:
      - 20newsgroups: https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html
      - bbc: http://mlg.ucd.ie/datasets/bbc.html
      - web of science: https://data.mendeley.com/datasets/9rw3vkcfy4/6
         
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
