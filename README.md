# ML_Group_09 - Repeat Purchase Prediction

This repository has our Machine Learning homework which predicts whether a customer will make another purchase within 90 days of their current purchase.

The pipeline, method choices and results are described in the accompanying PDF report.

The notebooks are in the notebooks folder and should be run in this order:
nb1_data_exploration.ipynb — Data exploration and main findings.
nb2_cleaning_data.ipynb — Data cleaning and comparison of preprocessing methods.
nb3_feature_work.ipynb — Comparison of categorical encoders and scalers.
nb4_selection_and_model.ipynb — Feature selection, model assessment and test predictions.

The data folder contains train.csv, test.csv, clientes.csv and sample_submission.csv.
nb2 generates data/interim/train_cleaned.csv and logs/train_cleaning_log.json, which are used by the later notebooks.
nb4 saves the final predictions to submissions/Homework_Group09_submission.csv, following the format of sample_submission.csv.

We used the machine_learning environment from class. You can find its packages in environment.yml. Open the notebooks from the notebooks folder and run them in the order listed above, using the machine_learning kernel.