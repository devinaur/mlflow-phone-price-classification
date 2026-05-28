# Phone Price Modelling

ML model that predicts phone price ranges using a preprocessed dataset. Trained with MLflow tracking.

## Pipeline Position
This is **Stage 2** of the phone price prediction pipeline.
It consumes the cleaned data produced by [phone-price-preprocessing](https://github.com/devinaur/phone-price-preprocessing).

## Files
- `modelling.py` — model training script
- `MLflowProject` — MLflow project config
- `conda.yaml` — environment dependencies
- `mlruns/` — logged MLflow runs (metrics, params, saved model)
- `phoneprice_preprocessing.csv` — cleaned input data (output from preprocessing repo)

## How to Run
conda env create -f conda.yaml
conda activate <env_name>
python modelling.py

## Requirements
Run the preprocessing repo first to generate `phoneprice_preprocessing.csv`, or use the file already included.
