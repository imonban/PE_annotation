# Radiology report annotation for Pulmonary Embolism

Welcome to the PE_annotation wiki!

A hybrid method–**Intelligent Word Embedding (IWE) **that combines neural embedding method with a semantic dictionary mapping technique for creating a dense vector representation of unstructured radiology reports.

We applied IWE to generate embedding of chest CT radiology reports from two healthcare organizations and utilized the vector representations to semi-automate radiology report categorization based on clinically relevant categorization related to the diagnosis of pulmonary embolism (PE).

Methodlogy:

Extract Impression;
Pre-process text;
Use pre-trained embedding to create vector;
Use pre-trained classification to generate annotation;
Generates annotation for PE positive (1 = PE positive) and PE acute (1 = PE acute);

Steps to create the annotations:
1. Install python (version >3) and pip
2. Unzip the folder
3. Install dependencies 
From a command prompt go inside the folder
 Type  pip install -r requirements.txt
4. Put the csv file with reports within the folder 'folder/Reports/' where reports are stored in ['Report Text'] column 
5. Run the code
From a command prompt go inside folder
Type  python 'PE report annotations.py'
Once promoted by the execution, provide the file name. Example: 'Stanford_PE_Tests.csv'
Give file name for storing the annotation. Example:'FILE_NAME.csv'
6. Find the annotated csv in 'folder/FILE_NAME.csv'


Find more detail in - Banerjee, Imon, Matthew C. Chen, Matthew P. Lungren, and Daniel L. Rubin. "Radiology report annotation using intelligent word embeddings: Applied to multi-institutional chest CT cohort." Journal of biomedical informatics 77 (2018): 11-20. https://www.sciencedirect.com/science/article/pii/S1532046417302575
