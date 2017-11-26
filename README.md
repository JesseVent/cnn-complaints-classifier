# Classify Kaggle Consumer Finance Complaints

## Train:

`python3 train.py ./data/consumer_complaints.csv.zip ./parameters.json`

A directory will be created during training, and the trained model will be saved in this directory.

## Predict:

`python predict.py ./trained_model_1511669634/ ./data/large_sample.json`
