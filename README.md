# Rocchio-Algorithm-Implementation-for-Relevance-feedback-in-Information-Retrieval
This repository has codes for implementing Rocchio Algorithm using both Tf-IDF and Word2Vec embedding. We also implement the algorithm using Query Expansion 

## Rocchio Algorithm formula:

![Formula](https://github.com/Subham07/Rocchio-Algorithm-Implementation-for-Relevance-feedback-in-Information-Retrieval/blob/master/Rocchio%20Algorithm.JPG)

Constants are:
alpha=1
beta=0.75
gamma is taken as 0 and 0.15 in some cases

## Dataset source
Dataset has been taken from: https://drive.google.com/open?id=1JuawXQmYVkjpfL3H0blqjDrqw8V1lHrC

## Query Format
Queries are of the form of XML File and we just extract text with the <desc> </desc> tags

## Document Format
Documents are of the form of XML File and we just extract text with the <TEXT> </TEXT> tags

## Pre-Processing
Document and Query Tokens have been Extracted in **PreProcessing.ipynb** file and stored in different csv files

## Query Expansion
Query Expansion has been calculated in **Query_Expansion_calculation.ipynb** file and data resulted is stored in csv file

## Algorithm Implementation Approches:
  1. **Rocchio_TfIdf_Query.ipynb** : Tf-IDF vectorizer is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated. Observations are seen twice using Gamma=0.15 and Gamma=0
  
  2. **Rocchio_TfIdf_QueryExpansion.ipynb** : Tf-IDF vectorizer is used to form vector for each Document and Expanded Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated. Observations are seen twice using Gamma=0.15 and Gamma=0
  
  3. **Rocchio_Word2Vec_Query1.ipynb** : Word2Vec is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated. Observations are seen using Gamma=0.15
  
  4. **Rocchio_Word2Vec_Query2.ipynb** : Word2Vec is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated. Observations are seen using Gamma=0
  
  5. **Rocchio_Word2Vec_QueryExpansion1.ipynb** : Word2Vec is used to form vector for each Document and Expanded Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated. Observations are seen using Gamma=0.15
  
  6. **Rocchio_Word2Vec_QueryExpansion2.ipynb** : Word2Vec is used to form vector for each Document and Expanded Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated. Observations are seen using Gamma=0
  
  
For any other code related queries, contact me:
mail id: subhamnagar@gmail.com

