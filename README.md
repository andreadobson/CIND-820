# Real or Fake?
## Classifying News Articles with Machine Learning Models

The code in this repository is intended to fullfill the requirements for the capstone project of the CIND 820 course at Toronto Metropolitian University. 

This research project aims to assess the capabilities of machine learning models to predict if a news article is real (i.e. factual), or fake (i.e. fictional). More specifically, I will attempt to answer the following research questions:
- Which aspect of an article allows for more accurate predictions: the title, or the text?
- To what degree do different methods of text vectorization (i.e. conversion of text to a numeric format suitable for modelling) affect the performance of the classification models used?
- Which classification model can most accurately predict if an article is real or fake?

The repository's contents are organized into three folders, each corresponding to a phase of the project:
1.  data preparation and cleaning
    * the folder contains .ipynb and .pdf files demonstrating how the data was prepared and cleaned
2. vectorization
    * this folder contains .ipynb and .pdf files demonstrating how the text was vectorized using two methods: TF-IDF and word2vec   
3.  modelling
    *  this folder contains .ipynb and .pdf files demonstrating how the vectorized text was used for different models
    *  there is a file for each type of model used: logistic regression, Naive-Bayes, and support vector machine
4. results
    * this folder contains .ipynb and .pdf files comparing and visualizing modelling results

A copy of the dataset has also been uploaded to the repository as "WELFake_Dataset.csv".
