# Project: Smart Recommendation System for a Basket Store

## How it works:
- Receives customer interactions (product viewing, purchase, etc.).
- Stores interactions.
- Trains a LightFM model.
- Sends recommendations based on user behavior.

## Run locally:
```bash
pip install -r requirements.txt
uvicorn main:app --reload
