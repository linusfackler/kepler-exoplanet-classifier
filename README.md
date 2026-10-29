# Kepler Exoplanet Classifier

A small machine learning project using NASA's Kepler Objects of Interest (KOI) dataset to predict whether an observed signal is more likely to be a confirmed exoplanet or a false positive.

I wanted to work on something astronomy-related and experiment with traditional machine learning models.

## What I did

- Explored and visualized the Kepler dataset (~9,500 observations).
- Trained a Logistic Regression model as a baseline.
- Trained and tuned a Random Forest classifier using cross-validation.
- Analyzed feature importance and how signal strength affects predictions.
- Used the final model to classify unresolved exoplanet candidates.

## Results

The tuned Random Forest achieved approximately **92% accuracy** on the held-out test set, compared to 81% with Logistic Regression.

I also applied the model to 1,982 unresolved candidates, of which 496 were classified as likely planets.

These are model predictions, not confirmed discoveries. The model is trained on previously classified observations and has limitations, particularly when dealing with weaker signals.

## Tools

Python, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Kaggle Notebooks.

## Files

- **Notebook (`.ipynb`)** — Full code, analysis, training, and results.
- **PDF** — Exported notebook for easier viewing.
- maybe at some point some frontend to use it for predictions if i feel like it

## Dataset

[NASA Kepler Objects of Interest Dataset](https://exoplanetarchive.ipac.caltech.edu/)

