# Prediction star rating of game reviews

### Description

Project created for predicting rating based on game review. It's goal is to improve my skills of training nlp models and learn new architecture - transformers.

### Model

Model based on transformers architecture, that are built with tutorial created by [Aladdin Persson](https://github.com/aladdinpersson). Model contains 3 transformers that are preceded by word-level and position-level embedding layers. After tranformers there are 3 fully connected layers. Model trained using [kaggle.com](kaggle.com) GPUs. Training took ~6 hours.

### Scores

Model achieved ~0.8 F1-score and ~0.87 ROC AUC score. Accuracy is not so important, beacouse even after augmentation data was quite imbalanced.