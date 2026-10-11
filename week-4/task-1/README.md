# Week 4 Task 1: Model REST API

This repository contains a REST API built with FastAPI that serves a fine-tuned model for IMDb movie review sentiment analysis.

## API Endpoints

### 1. Health Check
- **Endpoint:** `/`
- **Method:** `GET`
- **Description:** Checks if the API is running successfully.

**Example Response:**
```json
{
  "status": "running",
  "model": "Finetuning_Longformer_IMDb_movie_reviews_Classification"
}
{
  "review": "This movie was absolutely fantastic! The acting was great."
}
{
  "status": "success",
  "review": "This movie was absolutely fantastic! The acting was great.",
  "label": "LABEL_1",
  "score": 0.9987
}
