# SHL Assessment Recommendation System

## Overview
This project builds a GenAI-based recommendation system to suggest relevant SHL assessments given a job description or hiring query.

## Approach
- Used sentence embeddings (SentenceTransformers)
- Applied cosine similarity for retrieval
- Balanced technical (K) and behavioral (P) assessments implicitly via semantic similarity
- Generated predictions for the provided test set

## Files
- SHL_Assessment_Recommendation.ipynb: Core logic
- submission.csv: Predictions for the test set

## Notes
The pipeline is designed to scale to the full SHL catalog.
