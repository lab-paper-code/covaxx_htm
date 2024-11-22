# Dataset and Code
[SAC'25] HARIN: A Novel Metric for Hierarchical Topic Model Assessment

Our analysis is performed in the following steps:
1. Dataset Collection:
    - Our own: Korean twitter mentioning covid-19 vaccine(AstraZeneca, Janssen, Novavax, Moderna, Pfizer)
    - public:
      - 20 Newsgroups : https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html 
      - PubMed : https://huggingface.co/datasets/Gaborandi/Type_2_Diabetes_Mellitus_pubmed_abstracts
      - Yelp : https://www.yelp.com/dataset
      - arXiv : https://www.kaggle.com/datasets/spsayakpaul/arxiv-paper-abstracts
         
2. Preprocessing collected data
   - Data cleansing
   - Sentence correction
   - Removed stopwords
     
3. HTM model comparison & selection
   - Models : BERTopic, CluHTM, hLDA, and HyHTM  
   - Compute the HARIN (**H**ier**A**rchical ha**R**mony **IN**dex) score
   - Compute the HARIN score per model
     
4. Comparing HARIN with Human Judgment 
   - Conduct surveys to derive human scores and survey results(Questionaire.zip)
