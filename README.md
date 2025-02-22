
# TF-IDF Document Retrieval System

## Overview

The **TF-IDF Document Retrieval System** is a Python-based application that utilizes the Term Frequency-Inverse Document Frequency (TF-IDF) algorithm to identify and rank the top three most relevant documents in response to a user's query. This system is particularly useful for information retrieval tasks, enabling efficient and accurate document searches within a collection.

## Features

- **TF-IDF Vectorization:** Transforms text data into numerical vectors, capturing the importance of terms within documents.
- **Cosine Similarity Calculation:** Measures the similarity between the query vector and each document vector to assess relevance.
- **Ranking and Retrieval:** Sorts documents based on their similarity scores and retrieves the top three most relevant ones for each query.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Performance Evaluation](#performance-evaluation)

## Requirements

This project requires the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Samrawitgebremaryam/TF-IDF-Document-Retrieval-System.git
   ```

2. **Run the Notebook:**

   Navigate to the Project Directory:

   ```bash
   cd TF-IDF-Document-Retrieval-System
   ```

   Open the notebook (e.g., `document_retrieval.ipynb`) in Jupyter Notebook or any other compatible environment.
   
3. **Set Up a Virtual Environment:**

   ```bash
   python -m venv venv
   ```

4. **Activate the Virtual Environment:**

   - Windows:

     ```bash
     venv\Scripts\activate
     ```

   - macOS/Linux:

     ```bash
     source venv/bin/activate
     ```


## Usage

The system takes a user's query as input and retrieves the top three documents that are most relevant to the query, based on the TF-IDF and Cosine Similarity calculations.

1. **Input:** Enter a query in the provided input cell of the notebook.
2. **Output:** The system will display the top three documents ranked by relevance.

## Model Training

The TF-IDF algorithm is used to transform both the query and the documents into vectors. The cosine similarity between the query and each document vector is then computed to rank the documents based on their relevance to the query.

## Performance Evaluation

After retrieving the documents, the system ranks them and displays the top three documents that best match the user's query.

The relevance of the documents is determined using the following:

- **Cosine Similarity:** A metric used to measure the similarity between the query and documents based on their vector representation.
