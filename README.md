# Rocchio-Algorithm-Implementation-for-Relevance-feedback-in-Information-Retrieval
This repository has codes for implementing Rocchio Algorithm using both Tf-IDF and Word2Vec embedding. We also implement the algorithm using Query Expansion 

## Rocchio Algorithm formula:

![Formula](https://github.com/Subham07/Rocchio-Algorithm-Implementation-for-Relevance-feedback-in-Information-Retrieval/blob/master/Rocchio%20Algorithm.JPG)

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
  1. **Rocchio_TfIdf_Query.ipynb** : Tf-IDF vectorizer is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated. 
  
  2. **Rocchio_TfIdf_QueryExpansion.ipynb** : Tf-IDF vectorizer is used to form vector for each Document and Expanded Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated.
  
  3. **Rocchio_Word2Vec_Query1.ipynb** : Word2Vec is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated.
  
  4. **Rocchio_Word2Vec_Query2.ipynb** : Tf-IDF vectorizer is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated.
  
  5. **Rocchio_Word2Vec_QueryExpansion1.ipynb** : Tf-IDF vectorizer is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated.
  
  6. **Rocchio_Word2Vec_QueryExpansion2.ipynb** : Tf-IDF vectorizer is used to form vector for each Document and Query. Rocchio Algorithm is used and using modified query, relevant and non-relevant documents are calculated.

