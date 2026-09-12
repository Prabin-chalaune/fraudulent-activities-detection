# Fraud Detection Using Machine Learning and Graph Databases
The goal of this project is to identify **fraudulent activities in banking transactions** by combining **machine learning techniques** with **graph databases**. The project utilizes the **BankSim dataset**, a simulated dataset generated from a sample of transaction data from a Spanish bank. It explores fraud detection using both traditional transaction-level features and graph-based relationships between entities and transactions.

## Purpose of Source Files
### `Code/data-pre-processing.ipynb`
Contains scripts for **preprocessing and cleaning the BankSim dataset** to prepare the data for analysis and machine learning models.

### `Code/Fraud_Detection_Using_ML.py`
Builds **fraud detection models using intrinsic features** extracted from the BankSim dataset.

### `Code/Fraud_Detection_Using_Graph_DB.py`
Develops fraud detection models using a combination of **intrinsic transaction features and graph-based features** derived from relationships within the transaction network.

### `Code/neo4j_graphdb.cyp`
Contains **Neo4j Cypher queries** used to create, populate, and manage the graph database model using the BankSim dataset.

## Learning
This project demonstrates how **graph databases and machine learning can be integrated for banking fraud detection**. It focuses on using transaction-level features together with graph-based relationships to identify potentially fraudulent activities.

