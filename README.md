# information-retrieval

A series of projects implementing a search engine and various aspects of the information retrieval pipeline. 

## Retrieval Models

The objective of this project is to implement and compare various retrieval systems using vector space models and language models. The two main components are a program to parse the corpus of documents and index it with Elasticsearch and a query processor, which runs queries from an input file using a selected retrieval model.

## Indexer

The objective of this project is to implement an indexer, used in place of the Elasticsearch indexer. Then, generate the index from a set of documents and search the index to return documents relevant to a list of queries.

## Crawler 

For this project, I implemented a web crawler to construct a document collection focused on a particular topic. The 40,000 crawled documents and their relevant data, including inlinks and outlinks, were saved locally as individual text files and then merged into a group index using Elasticsearch.

## PageRank and HITS

This project computes link graph measures, PageRank and HITS, for a set of crawled documents using an adjacency matrix.

## Relevance Assessments

This project implements a script to score information retrieval relevance, comparing a retrieval model's scores on a set of documents to a file of manually assessed scores for the same documents.

## Machine Learning for Information Retrieval 

This project represents documents as numerical features and applies machine learning to obtain retrieval ranked lists.
