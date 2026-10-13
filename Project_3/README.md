# COMS 5790 - Project 3: RAG System

 Kaggle Username: Giuliano Pitari

## Project Overview
This repository contains the implementation of a Retrieval-Augmented Generation (RAG) system designed to answer domain-specific questions based on messy lecture transcripts. The system explicitly handles formatting noise, extracts contextually faithful facts, and formats strict answers (e.g., Yes/No, exact blanks) to combat hallucinations and parametric memory conflicts.

## Repository Structure
- `Project3_RAG_Pitari.ipynb`: The main Colab notebook containing the end-to-end pipeline (Preprocessing, Indexing, Retrieval, Generation, and Submission).
- `README.md`: Execution instructions.

## How to Run the Code
1. Open the `Project3_RAG_Pitari.ipynb`.
2. Ensure you have the required datasets downloaded:
   - `documents.txt`
   - `QA_test.csv`
3. Upload these two files directly to the root directory of your environment.
4. Run all cells sequentially. The first cell will automatically install the required dependencies (LangChain, FAISS, SentenceTransformers).
5. The final cell will generate a `submission.csv` file formatted properly for the Kaggle Private Leaderboard evaluation.

