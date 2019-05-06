# Writing Style Analysis by Gender and Gender Classification
Final Project for DS 5559 - Exploratory Text Analytics

### Team members
  - Will Gleave  (SWG8JQ)
  - Sameer Singh  (SS8GC)

### Documents
#### Jupyter Notebooks
  - ETA - Visualization v1.0.ipynb: Contains visualization of the data, with NLTK Vader sentiment, and an interactive cosine similarity measure tool
  - PCA-Final.ipynb: Contains visualization of the data based on Principal Component Analysis.  
  - GenderF4-Final.ipynb: Contains the processing required to create the sample dataset used for processing i.e. F4 compliant dataset. 
  - Clustering and Interactive Visualization-Final.ipyb: Contains visualization of dataset using k-means clustering technique and an interactive Function for K means Clustering.
  - ETA - Prediction v1.0.ipynb: Contains a classification model, which uses features such as char n-gram, word n-gram, NLTK sentiment, Latent Dirichlet Allocation, with Random Forest and XGBoost algorithms 

#### Datasets
  - sample3 (1).csv.zip: Contains processed token table for 10k sample blog posts from F4 processing
  - sampleorig.csv: Contains sampled unprocessed corpus of 10k blog posts.  Also includes some author metadata.
  - vocab.csv: Contains vocab table from F4 processing
  - Note: we attempted to write the tfidf table to csv, but the file was over 11gb and could not be finished due to the size of our AWS instance.  If necessary we can try again to generate this csv, but for now, we are hoping the printed out head of the tfidf table in the GenderF4 notebook will suffice.
