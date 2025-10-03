Code for the Pilot "Digitized deeds: A pilot study exploring methods for extracting information from handwritten bill of sales, Johan Ericsson" (2023-2024)

# Digitising Deeds

**Digitising Deeds** is the codebase from the pilot project *“Digitized deeds: A pilot study exploring methods for extracting information from handwritten Bill of Sales”* (2023–2024), led by CDH Uppsala.  
It provides tooling, notebooks, and pipelines for processing and extracting structured data from historical handwritten documents (deeds, bills of sale, etc.).

## Table of Contents

- [Background & Goals](#background--goals)  
- [Files Details](#files-details)  
- [Usage](#usage)  
- [Acknowledgements](#acknowledgements)  
- [License](#license)  

## Background & Goals

Historical deeds, contracts, and bills of sale are valuable sources of socioeconomic, legal, and genealogical information. However, many are handwritten, making large-scale extraction of structured data challenging.  
The aim of this project is to explore and prototype workflows for **recognizing entities**, and **structuring** data from such documents using machine learning, and language/vision models.

## Files Details

- **Mixtral-hf.ipynb** – experiments and demos involving the Mixtral MoE model (and related huggingface workflow). Notebook used at the end of the project to extract entities and structure output into data sheets.  
- **htrflow_core-LLM_pipeline.ipynb** – Experiments for HTR and structuring output (minimal code). 
- **test_htrflow_core.ipynb** – Experiments for HTR and structuring output.

## Usage

- Download or clone the repository.
- Install jupyter notebook.
- Run htrflow_core-LLM_pipeline.ipynb, it has code to clone Riksarkivet's HTRFlow app (https://github.com/AI-Riksarkivet/htrflow_app/tree/main). Follow their instructions to install dependencies if something is missing. 


## Acknowledgements

We built parts of our pipeline using the HTRflow ecosystem developed by the AI lab at the Swedish National Archives (Riksarkivet). In particular, we leveraged htrflow_app for Handwritten Text Recognition.

## License

This project is open source. 
