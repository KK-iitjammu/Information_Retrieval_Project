# Information_Retrieval_Project
Query Processing with Elasticsearch &amp; improvement using Query Expansion with Rocchio Algorithm

## Project Details
The aim of this project is to utilize the Elasticsearch functionalities for Information Retrieval task and in that specifically for query processing and retrieving top k results (i.e. documents) for the given query.

This project involves writing two python notebooks:
1. First notebook has a program parse the FIRE 2010 english Dataset and index all the documents using Elasticsearch APIs and then retrieving top k documents for all the queries in dataset.
2. Second notebook has a program to improve above results using Query Expansion and Rocchio Algorithm.

### Getting Started
* Download and install [elasticsearch](http://www.google.fr/ "elasticsearch") for running notebook 1
* Download [FIRE_2010_english_Dataset](https://drive.google.com/file/d/1JuawXQmYVkjpfL3H0blqjDrqw8V1lHrC "FIRE_2010_english_Dataset") for both the notebooks

### Notebook 1
**Indexing.ipynb** is the program to parse the FIRE 2010 english Dataset and index all the documents using Elasticsearch APIs and then retrieving top k documents for all the queries in dataset.
Requirements to run this notebook successfully:
1) Elasticsearch and dataset downloaded in the same folder 
2) A file named 'listOfrelevantDocsList.txt' which is generated in notebook 2 and used for calculating evaluation metric(mean average precision)

### Notebook 2
**Query_Expansion_with_Rocchio_v2.ipynb** is a program to improve above results using Query Expansion and Rocchio Algorithm.
Requirements to run this notebook successfully:
1) Dataset downloaded in the same folder 
2) Two files named 'top_10_relevant_list.txt'(generated in first module and used in 2nd to improve results) and 'rel_doc_list.txt' (contains list of relevant documents for each query from dataset)
