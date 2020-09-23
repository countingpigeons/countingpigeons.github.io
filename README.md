# Analytics Portfolio
A collection of my recent data science and engineering projects and some custom visualizations. 

### Readership Analytics for Sellside Banks 
  - **Type:** Business Intelligence.
  - **Description:** A Business Intelligence portal for investment banks to measure the market penetration of their published research documents versus competitors over multiple slices. Implementated in Microstrategy Cloud. Modeled data (conceptual, logical, physical, dimensional); wrote and scheduled a 70+ step daily ETL in the cloud; created all reports, dashboards, and custom analytical SQL; and QA'd embedding into production as a web-app with Single-Sign-On (SSO). 
  - **Skills:** SQL, Conceptual & Dimensional Modeling, ETL scripting, Microstrategy Architect, Microstrategy Desktop, Informatica.
  - **Anonymized sample images:**
    - conceptual model | main dashboard | documents dashboard 
      -------|------|--------
      ![RBA - conceptual model](README_rba_conceptual-model.jpg?raw=true "Visio") | ![RBA - main dashboard](README_rba_main-anonymized.jpg?raw=true "BI Dashboard") | ![RBA - documents dashboard](README_rba_documents-anonymized.jpg?raw=true "BI Dashboard")

### Titanic
  - **Type:** Machine Learning / Jupyter Notebook
  - **Description:** An independent project using 4 independent classification models, various voting ensembles, and features I haven't seen elsewhere to score in the top 8% on the public leaderboard.
  - **Skills:** Pandas, Numpy, Scikit-learn: Logistic Regression, RandomForest, AdaBoost, Tensorflow, Seaborn, Matplotlib Object Model, regex.
  - **Link:** [Kaggle](https://www.kaggle.com/countingpigeons/titanic-survival-cross-validated-voting-ensembles)
  - **Custom Visualizations:**
    - fillna w/ sampling | feature importances | deep model accuracy | model comparison | identify difficult cases
      ------------|------|--------|--------|------------
      ![Titanic - fill null ages with random sampling](README_titanic_fill-null-ages.jpg?raw=true "Histogram") | ![Titanic - feature importances](README_titanic_scikit-feature-importances.jpg?raw=true "BoxPlots") | ![Titanic - deep model accuracy](README_titanic_deep-model-accuracy-detail.jpg?raw=true "MixedChart") | ![Titanic - model comparison](README_titanic_model-comparisons-over-10-folds.jpg?raw=true "FormattedTable") | ![Titanic - investigate model failures](README_titanic_investigate-model-failures.jpg?raw=true "FacetGrid")

### Winning Solitaire Decks
  - **Type:** Machine Learning / Jupyter Notebook
  - **Description:** An independent project from a personal curiosity using Tensorflow deep models trained on various features over 10K decks of cards which won or lost at solitaire in a self-written simulator (below). Found no statistically-significant difference between winning and losing decks and thus couldn't generalize features in shuffled decks of cards that tend to win in solitaire (e.g. how balanced are the colors or values across the deck etc...).
  - **Skills:** Pandas, Numpy, Tensorflow, AdaBoost Regression, Seaborn, Matplotlib Object Model
  - **Link:** [Kaggle](https://www.kaggle.com/countingpigeons/predicting-winning-solitaire-decks)
  - **Custom Visualizations:**
    - winningdeck pairwise values | pairwise detail | model accuracy | deck stats: color balance | deck stats: contiguousness
      ------------|------|--------|--------|------------
      ![Solitaire - pairwise locations - multi](README_solitaire_pairwise_card_values_multi.jpg?raw=true "ScatterGrid") | ![Solitaire - pairwise locations - single](README_solitaire_pairwise_card_values_single.jpg?raw=true "Scatter") | ![Solitaire - Model accuracy - added noisy explanatory](README_solitaire_model-accuracy-w-noisified-num-moves.jpg?raw=true "MixedChart") | ![Solitaire - stats - color balance](README_solitaire_stats-color-balance.jpg?raw=true "Scatter") | ![Solitaire - stats - contiguous vs chunky](README_solitaire_stats-contiguous-vs-chunky.jpg?raw=true "Scatter")

### Solitaire Simulator
  - **Type:** Engineering
  - **Description:** A Solitaire simulator from scratch using "pure" object-oriented Python (only random, argparse, and logging modules). 1,000+ lines. By default, outputs a .csv file with 10K decks of training data. For each deck, this includes deck-order, win/lose flag, and # moves. 
  - **Skills:** Python, object-oriented programming, software design.
  - **Link:** [github](https://github.com/countingpigeons/winningdeck/blob/master/winning_deck.py)
