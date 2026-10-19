# Collaborative filtering · ETH CIL 2024

Team project for ETH Zürich's Computational Intelligence Lab, by Giacomo Fiorindo, Adam Mernissi Arifi, Mehdi Ziazi, and Pierre-Louis Bravais (team **Skill_issue**). We compared matrix factorization, autoencoders, neural collaborative filtering, and LightGCN, then blended predictions from eight models. The ensemble achieved **0.96677 RMSE** on the Kaggle public test set, and team **Skill_issue placed 5th** on the [competition leaderboard](https://www.kaggle.com/competitions/ethz-cil-collaborative-filtering-2024/leaderboard).

The [report](report.pdf) describes the models and results. Model notebooks are in the root directory; additional baselines and experiments are in their named folders.

## Run

Install the packages in `requirements.txt` and open the notebooks in Jupyter or Google Colab. The notebooks expect the course's `data_train.csv` and `sampleSubmission.csv`. Each model writes prediction files for the final [`ensemble.ipynb`](ensemble.ipynb); the data, intermediate predictions, and generated submission are excluded from this repository.
