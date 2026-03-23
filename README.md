# Sasaki_iHARP-ML-Challenge-2_PredictingCoastalFloodingEvents
A variety of models for predicting coastal flooding events for iHARP-ML-Challenge-2

Competition repo: https://github.com/iharp-institute/iHARP-ML-Challenge-2 \
Codabench: https://www.codabench.org/competitions/10801/

## Models include in this repo

### XGBoost
Provided model with a few modifications

### Seq2Seq LSTM
Preserves temporal order in data and to allow prediction from prior day to be communicated to the model forecasting the next day

### Simple LSTM (no decoder)
Easier training while still respecting the sequence nature of the data, given the limited data (5 stations) and short training period.

### Random Forest Regressor
Limits depth to prevent overfitting given the limited data (5 stations)
