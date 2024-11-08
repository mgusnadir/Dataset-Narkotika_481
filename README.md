# Narkotika dan Psikotropika Legal Case Dataset

**Name :** Muhammad Gus Nadir  
**NIM  :** 202110370311481

## Project Overview
This dataset is designed for the analysis and classification of Narkotika dan Psikotropika cases under PIDANA KHUSUS jurisdiction in Jakarta Barat. By focusing specifically on narcotics and psychotropic criminal cases, this dataset aims to support research in legal NLP (Natural Language Processing) tasks, such as case document indexing, information retrieval, and classification.

## Directory Structure

├── Dataset  
│   └── Narkotika.zip

├── Overview  
│   └── Overview.xlsx


### Dataset Content and Purpose

- **Dataset/Narkotika.zip**  
  This ZIP file contains a collection of court rulings in PDF format specific to Narkotika and Psikotropika cases in Jakarta Barat. Each document captures critical details about case rulings and provides essential insights into legal decisions in narcotics-related criminal cases.

- **Overview/Overview.xlsx**  
  This Excel file provides a summary or meta-information of the documents in Narkotika.zip. It include fields such as:
  1. No: Sequential number of the case.
  2. No Putusan: Unique ruling identifier for each case.
  3. Lembaga Peradilan: Judicial institution that issued the ruling.
  4. Barang Bukti: Types and quantities of evidence presented in the case.
  5. Amar Putusan: Summary of the court's decision.

## Getting Started

1. **Unzip Dataset**  
   Extract `Narkotika.zip` in the Dataset folder to access the PDF files.

2. **Data Pre-processing**  
   Each PDF document should be preprocessed for text extraction, tokenization, and indexing. Suggested preprocessing includes removing noise, identifying key entities (e.g., dates, judicial institution, and evidence types), and structuring the data.

3. **Loading Metadata**  
   Use `Overview.xlsx` as an initial guide for each document’s metadata. This file can facilitate exploration and provide structured data for case classification.

## Resources for Additional Data

For further case rulings or to contribute additional data, you can refer to the [Direktori Putusan resource](https://putusan3.mahkamahagung.go.id/beranda.html). This platform provides an extensive collection of Indonesian court rulings, which can be used to augment or extend this dataset.