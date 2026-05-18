# Stance Detection using BERTweet

This project implements stance detection on the SemEval-2016 Task 6 Twitter dataset using the BERTweet transformer model.

## Files
- `preprocessing.ipynb` — data cleaning, EDA, target-aware formatting
- `bertweet_experiments.ipynb` — training, evaluation, visualisations

## Model
- BERTweet (`vinai/bertweet-base`)
- Weighted cross entropy loss
- Hugging Face Transformers + PyTorch
