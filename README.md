# Apple TV+ Data Analysis

This repository contains a visual data exploration of the Apple TV+ catalog using IMDb ratings, vote counts, and content metadata.

## Dataset

- Source: [Kaggle - Full Apple TV+ Dataset](https://www.kaggle.com/datasets/octopusteam/full-apple-tv-dataset)
- Dataset includes over 18,000 titles from Apple TV+
- Key fields: `title`, `type`, `genres`, `releaseYear`, `imdbAverageRating`, `imdbNumVotes`, `availableCountries`

## Objectives

The goal of this project is to:

- Identify the highest-rated Apple TV+ content based on IMDb scores
- Analyze the distribution of IMDb ratings across all titles
- Highlight the most voted (audience-engaged) titles

## Analyses Performed

1. **Top 10 Apple TV+ Titles by IMDb Rating**  
   A sorted bar chart visualizing the highest-rated content.

2. **IMDb Rating Distribution**  
   A histogram showing how Apple TV+ titles are distributed by IMDb score.

3. **Top 10 Apple TV+ Titles by IMDb Vote Count**  
   Visualizing the most audience-engaged titles based on the number of IMDb votes.

## Tools and Technologies

- Python 3.12
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

## Folder Structure
```
apple-tv-plus-data-analysis/
│
├── data/
│   └── apple_tv_dataset.csv
│
├── notebooks/
│   └── apple_tv_analysis.ipynb
│
├── output/
│   └── figures/ (optional)
│
└── README.md
```
## Author

Akash Guha  
GitHub: [akashguha9](https://github.com/akashguha9)
