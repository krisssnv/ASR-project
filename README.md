# ASR Project

This repository contains notebooks and analysis scripts for automatic speech detection/classification of dementia experiments. It covers data preprocessing, model training, feature extraction, and result visualization for both interpretable and non-interpretable feature sets.

## Main Parts

- `pre_processing_ASR.ipynb` - preprocessing and data preparation.
- `NIF_TrainModels.ipynb` - training models with non-interpretable features.
- `Train_eGeMAPS_and_ComParE2016_combined_commented.ipynb` - training interpretable baseline models.
- `Interpretable features/modelstrain.ipynb` - training and evaluating interpretable feature-based models.
- `plotting(1).ipynb` - plotting and comparison of results.
-   `SPLIT_clean.ipynb`     - prepares data splits
## Data And Results

- `Interpretable features/` stores model outputs, metrics CSVs, and analysis notebooks for interpretable experiments.
- `Non_Interpretable_Features/` stores notebooks and notes for embedding-based / non-interpretable feature extraction.

## Typical Workflow

1. Run preprocessing and feature extraction to prepare the dataset.
2. Split data into TRAIN/TEST 
3. Train models for the feature sets you want to compare, using the predefined datasplits
4. Collect the generated CSV metrics and predictions.
5. Use the plotting notebook to summarize and visualize results.

## Data used is from DementiaBank corpus.
