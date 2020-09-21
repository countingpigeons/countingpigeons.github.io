# Analytics Portfolio
A collection of my recent data science and engineering projects and some custom visualizations. 

### Titanic
  - **Type:** Machine Learning / Jupyter Notebook
  - **Description:** An independent project using 3 scikit-learn models and 
  - **Skills:** Pandas, Numpy, Scikit-learn:  Logistic Regression, RandomForest, AdaBoost, Tensorflow, Seaborn, Matplotlib Object Model
  - **Link:** [Kaggle](https://www.kaggle.com/countingpigeons/titanic-survival-cross-validated-voting-ensembles)
  - **Custom Visualizations:**
    - fillna w/ sampling | feature importances | deep model accuracy | model comparison | identify difficult cases
      ------------|------|--------|--------|------------
      ![Titanic - fill null ages with random sampling](README_titanic_fill-null-ages.jpg?raw=true "Histogram") | ![Titanic - feature importances](README_titanic_scikit-feature-importances.jpg?raw=true "BoxPlots") | ![Titanic - deep model accuracy](README_titanic_deep-model-accuracy-detail.jpg?raw=true "MixedChart") | ![Titanic - model comparison](README_titanic_model-comparisons-over-10-folds.jpg?raw=true "FormattedTable") | ![Titanic - investigate model failures](README_titanic_investigate-model-failures.jpg?raw=true "FacetGrid")

### Klondike Solitaire
  - **Type:** Machine Learning / Jupyter Notebook
  - **Description:** An independent project using Tensorflow deep models trained on various features over 10K decks of cards tagged whether they won at solitaire in a self-written simulator (below). Found no statistical difference between winning and losing decks and thus couldn't generalize features in a shuffled deck of cards that lead toward a win in solitaire.
  - **Skills:** Pandas, Numpy, Tensorflow, AdaBoost Regression, Seaborn, Matplotlib Object Model
  - **Link:** [Kaggle](https://www.kaggle.com/countingpigeons/predicting-winning-solitaire-decks)
  - **Custom Visualizations:**
    - winningdeck pairwise values | pairwise detail | model accuracy | deck stats: color balance | deck stats: contiguousness
      ------------|------|--------|--------|------------
      ![Solitaire - pairwise locations - multi](README_solitaire_pairwise_card_values_multi.jpg?raw=true "Scatter") | ![Solitaire - pairwise locations - single](README_solitaire_pairwise_card_values_single.jpg?raw=true "FormattedTable") | ![Solitaire - Model accuracy - added noisy explanatory](README_solitaire_model-accuracy-w-noisified-num-moves.jpg?raw=true "MixedChart") | ![Solitaire - stats - color balance](README_solitaire_stats-color-balance.jpg?raw=true "Scatter") | ![Solitaire - stats - contiguous vs chunky](README_solitaire_stats-contiguous-vs-chunky.jpg?raw=true "Scatter")

