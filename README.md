# Rafeeq : AI Car Recommendation System

An Egypt-focused conversational assistant that helps car buyers choose the car that fits their budget, needs, and lifestyle, in Arabic and English.

> Graduation project for DEPI, Microsoft Machine Learning Engineer Track, Round 5.



## Problem Statement

Choosing a car is complicated, especially for people unfamiliar with the market. Buyers face information overload, unclear requirements, time-consuming research across many websites, and a lack of personalized guidance, since most platforms rely only on fixed filters.

Rafeeq addresses this with a conversational recommendation system that understands the user's requirements, analyzes vehicle data, and gives personalized, explainable recommendations.

## Features

- **Conversational preference gathering:** understands budget, usage, and preferences from free text (Arabic/English).
- **Personalized recommendation engine:** multi-criteria ranking of cars, refined during the conversation.
- **Explainable recommendations and comparison:** specs, estimated prices, why each car matches, pros and cons, and side-by-side comparison.
- **Grounded answers (RAG):** the chatbot answers from retrieved data in the car database to avoid made-up information.
- **Market analytics dashboard:** price and trend insights by brand, year, and body type.
- **Dealership mode (optional):** limits recommendations to a specific dealership's inventory.


## Tech Stack

- **Frontend:** React
- **Backend:** Python, FastAPI
- **Database:** PostgreSQL or SQLite
- **ML/NLP:** Scikit-learn, [embedding model], [FAISS or ChromaDB]
- **LLM:** [pretrained model] with Retrieval-Augmented Generation
- **Data processing and visualization:** Pandas, NumPy, Plotly

## Repository Structure

```
docs/        Project proposal and documentation
data/        Dataset description and data files
notebooks/   Exploration and experiments
src/         Data processing, recommender, NLP, and RAG code
backend/     API server
frontend/    User interface
models/      Saved models and instructions
```


## Project Timeline

| Week | Focus |
|---|---|
| 1 | Planning, data collection and setup |
| 2 | Recommendation engine and application core |
| 3 | Conversational layer and explainable recommendations |
| 4 | Evaluation, refinement and final presentation |


## Team

- TL: Salma Atef Bakry
- Shahd Amr Muhammad Wassel 
- Sondos Mohamed Galal Abdallah
- Amira Sabry Hemeida 
- Renad Eid Abdelfatah Borham
- Supervisor: Eng. George Samuel 
