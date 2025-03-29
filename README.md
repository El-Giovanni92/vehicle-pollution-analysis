# Vehicle Pollution Analysis  

## Introduction  

This project focuses on analyzing the environmental impact of vehicles registered in Sicily up to 2020, using open-source datasets. The main objective is to explore the correlation between vehicle EURO category, air pollution levels, and local temperature variations. The project adopts a **Linked Open Data** approach to enhance data accessibility and representation.  

## Technologies & Data Formats  

The project utilizes the following languages and data formats:  

- **Python** for data collection, processing, and analysis.  
- **SQL** for dataset management and queries.  
- **SPARQL** for querying the RDF data.  
- **RDF (Turtle format - TTL)** for structured data representation.  
- **OWL** for ontology creation to define the domain knowledge.  

## Objective  

The analysis aims to:  

- Extract and clean data from publicly available open datasets.  
- Convert the data into Linked Open Data and define its semantics using an OWL ontology.  
- Query the RDF data using SPARQL.  
- Provide interactive visualizations for better data interpretation.  

## Cloning the Repository

This repository uses **Git LFS** to store large files.  
Before cloning the repo, make sure Git LFS is installed.  

### Install Git LFS
If you haven’t installed Git LFS yet, run the following command:

```bash
git lfs install
```
### Clone the repository
After installing Git LFS, clone the repository normally:

```bash
git clone https://github.com/tuo-utente/tuo-repository.git
```
If necessary, you can manually fetch the large files:

```bash
git lfs pull  
```

## Execution

1. **Open the main file** [`progetto.ipynb`](progetto.ipynb) in Jupyter Notebook.  
2. **Download the required datasets** using the links provided within the notebook.  
3. **Follow the instructions** and **execute the cells sequentially** to reproduce the analysis.  
4. **Analyze the results**, including interactive visualizations within the notebook.  

### Additional Files  

[**`progetto.pdf`**](progetto.pdf) provide a static version of the study for documentation purposes.  

### Contributors 

[@madoverflow](https://github.com/madoverflow) 
