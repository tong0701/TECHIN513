# Music-to-Imagine System (Team 18)

A music energy classification system that extracts DSP features from audio and uses SVM to classify songs into **Low** / **Medium** / **High** energy states, then maps the result to visual output.

## Tech stack

- Python
- librosa
- scikit-learn
- matplotlib
- pandas

## Dataset

[GTZAN](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) — not included in this repo. Download from Kaggle and place in `Data/` if you need to regenerate features.

## How to run

1. Install dependencies: `pip install librosa scikit-learn matplotlib pandas`
2. Open `513Final.ipynb` and run all cells.
