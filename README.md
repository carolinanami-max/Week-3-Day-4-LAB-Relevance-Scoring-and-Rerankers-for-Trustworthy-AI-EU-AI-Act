# RAG Pipeline Optimization - Relevance Scoring and Rerankers

## What This Project Does
This project demonstrates key techniques for improving RAG (Retrieval-Augmented Generation) pipelines:

1. **Query Improvement** - Making questions more specific to get better answers
2. **Parent Document Retrieval** - Splitting long documents into searchable chunks
3. **Relevance Scoring & Reranking** - Teaching AI to grade and sort answers by quality
4. **Metadata Filtering** - Adding labels to documents for better searching

## Files in This Project
- `notebooks/01_rag_pipeline.ipynb` - Main notebook with all the code
- `requirements.txt` - List of Python packages needed
- `.env` - Your API keys (keep this secret!)

## How to Use
1. Install packages: `pip install -r requirements.txt`
2. Add your API keys to `.env`
3. Open and run the notebook

## What We Learned
- How to make questions more specific for better searching
- How to split documents into smaller pieces
- How to score and rank answers by relevance
- How to filter documents using labels (metadata)