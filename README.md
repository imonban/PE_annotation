# PE_annotation

Welcome to the PE_annotation wiki!

A hybrid method–**Intelligent Word Embedding (IWE) **that combines neural embedding method with a semantic dictionary mapping technique for creating a dense vector representation of unstructured radiology reports.

We applied IWE to generate embedding of chest CT radiology reports from two healthcare organizations and utilized the vector representations to semi-automate radiology report categorization based on clinically relevant categorization related to the diagnosis of pulmonary embolism (PE).

Methodlogy:

Extract Impression
Pre-process text
Use pre-trained embedding to create vector
Use pre-trained classification to generate annotation
Generates annotation for PE positive (1 = PE positive) and PE acute (1 = PE acute)

Steps to create the annotations:
extract the zip
Run the PE report annotations.exe file in '/dist/' 
Input a csv file with 'Report Text' column 

Find more detail in - Banerjee, Imon, Matthew C. Chen, Matthew P. Lungren, and Daniel L. Rubin. "Radiology report annotation using intelligent word embeddings: Applied to multi-institutional chest CT cohort." Journal of biomedical informatics 77 (2018): 11-20. https://www.sciencedirect.com/science/article/pii/S1532046417302575
