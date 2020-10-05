# Analytics Portfolio
A collection of my recent data science, business intelligence, and engineering projects and some custom visualizations. 

### Readership Analytics for Sellside Banks 
  - **Type:** Business Intelligence.
  - **Description:** A Business Intelligence portal for investment banks to measure the market penetration of their published research documents versus competitors. Implemented in Microstrategy Cloud. Modeled data (conceptual, logical, physical, dimensional); built data warehouse; wrote and scheduled the ETL in the cloud to process 100K+ rows daily; created all reports, dashboards, and custom analytical SQL; and QA'd embedding into production as a web-app with Single-Sign-On (SSO). 
  - **Skills:** SQL, Conceptual & Dimensional Modeling, ETL scripting, Microstrategy Architect, Microstrategy Desktop, Informatica
  - **Sample images:**
    - conceptual model | main dashboard | documents dashboard 
      -------|------|--------
      ![RBA - conceptual model](README_rba_conceptual-model.jpg?raw=true "Visio") | ![RBA - main dashboard](README_rba_main-anonymized.jpg?raw=true "BI Dashboard") | ![RBA - documents dashboard](README_rba_documents-anonymized.jpg?raw=true "BI Dashboard")

### Titanic
  - **Type:** Machine Learning / Jupyter Notebook
  - **Description:** An independent Python project using 4 independent classification models, various voting ensembles, and features I haven't seen elsewhere to score in the top 8% on the Kaggle public leaderboard.
  - **Skills:** Pandas, Numpy, Tensorflow, Logistic Regression, Random Forest, AdaBoost, Seaborn, Matplotlib Object Model, regex
  - **Link:** [Kaggle](https://www.kaggle.com/countingpigeons/titanic-survival-cross-validated-voting-ensembles)
  - **Custom Visualizations:**
    - fillna w/ sampling | feature importances | deep model accuracy | model comparison | identify difficult cases
      ------------|------|--------|--------|------------
      ![Titanic - fill null ages with random sampling](README_titanic_fill-null-ages.jpg?raw=true "Histogram") | ![Titanic - feature importances](README_titanic_scikit-feature-importances.jpg?raw=true "BoxPlots") | ![Titanic - deep model accuracy](README_titanic_deep-model-accuracy-detail.jpg?raw=true "MixedChart") | ![Titanic - model comparison](README_titanic_model-comparisons-over-10-folds.jpg?raw=true "FormattedTable") | ![Titanic - investigate model failures](README_titanic_investigate-model-failures.jpg?raw=true "FacetGrid")

### Winning Solitaire Decks
  - **Type:** Machine Learning / Jupyter Notebook
  - **Description:** An independent Python project from a personal curiosity using Tensorflow deep models trained on various features over 10K decks of cards which won or lost at solitaire in a self-written simulator (below). Found no statistically-significant difference between winning and losing decks (e.g. how balanced are the colors or values across the deck etc...) and determined that winning decks are exceptionally sensitive to small differences in the starting order and thus couldn't be generalized.
  - **Skills:** Pandas, Numpy, Tensorflow, AdaBoost Regression, Seaborn, Matplotlib Object Model
  - **Link:** [Kaggle](https://www.kaggle.com/countingpigeons/predicting-winning-solitaire-decks)
  - **Custom Visualizations:**
    - winningdeck pairwise values | pairwise detail | model accuracy | deck stats: color balance | deck stats: contiguousness
      ------------|------|--------|--------|------------
      ![Solitaire - pairwise locations - multi](README_solitaire_pairwise_card_values_multi.jpg?raw=true "ScatterGrid") | ![Solitaire - pairwise locations - single](README_solitaire_pairwise_card_values_single.jpg?raw=true "Scatter") | ![Solitaire - Model accuracy - added noisy explanatory](README_solitaire_model-accuracy-w-noisified-num-moves.jpg?raw=true "MixedChart") | ![Solitaire - stats - color balance](README_solitaire_stats-color-balance.jpg?raw=true "Scatter") | ![Solitaire - stats - contiguous vs chunky](README_solitaire_stats-contiguous-vs-chunky.jpg?raw=true "Scatter")

### Solitaire Simulator
  - **Type:** Data Engineering
  - **Description:** A Solitaire simulator from scratch using "pure" object-oriented Python (only random, argparse, and logging modules) to create clean training data for a Machine Learning project. 1,000+ lines. Outputs a .csv file with 10K rows and 54 columns including the deck-order, a win/lose flag, and # moves played for each deck. 
  - **Skills:** Python, object-oriented programming, software design
  - **Link:** [GitHub](https://github.com/countingpigeons/winningdeck/blob/master/winning_deck.py)

### Flickr2Table
  - **Type:** Data Engineering
  - **Description:** An independent project for a friend using the APIs of Flickr and Airtable to mirror daily any new photos added to a Flickr album in a searchable Airtable spreadsheet/database. The Airtable mobile app can then be used while in the field to research previously seen flowers. Two Python processes run daily through Apache Airflow. Multiple photos of the same flower/plant are combined into single records and new text found in the Flickr description field is parsed dynamically into new Airtable columns as needed.
  - **Skills:** Python, JSON, REST API, Oauth1, Apache Airflow, regex
  - **Link:** [GitHub](https://github.com/countingpigeons/flickr2table)
  - **Sample Images:**
    - flickr album | > apache airflow > | airtable       
      --------|------|--------
      ![Flickr2Table - flickr album](README_flickr2table_flickr-album-view.png?raw=true "Photo") | ![Flickr2Table - apache airflow](README_flickr2table_airflow-tree-view.png?raw=true "Photo") | ![Flickr2Table - airtable](README_flickr2table_airtable-filtered.png?raw=true "Photo")

### SuperBridge
  - **Type:** Data Engineering
  - **Description:** The default tool for engineering, QA, and customer-support to explore and update the Production Oracle DBoR at StarMine. Proposed the project, designed the views and UX, and provided all SQL statements and scripts (which I'd developed as a customer support engineer). This allows users to research underlying data in the same format as it appears on the product, make changes, trigger tasks, and automatically run all required clean-up and re-calculation tasks after manual updates.
  - **Skills:** SQL, Oracle, software design
  - **Image:**
    - ![SuperBridge](README_superbridge.jpg?raw=true "Photo") 
      
