# UF March Madness Predictor

## Overview

UF March Madness Predictor is a project developed for the Kaggle competition "March Machine Learning Mania 2025" in collaboration with INFORMS at UF. The goal is to build a predictive model that forecasts NCAA tournament outcomes by estimating win probabilities for every possible team matchup and simulating entire tournament brackets. The project leverages various data sources—including KenPom rankings, NET rankings, Sagarin ratings, and more—to enhance prediction accuracy.

## Competition Details

- **Event:** March Machine Learning Mania 2025  
- **Host:** Kaggle  
- **Format:** Single-elimination NCAA tournament with 68 teams (bracket predictions must be valid)  
- **Objective:** Predict the outcomes of both Men's and Women's brackets by building a win probability model and a bracket simulator  
- **Prize Pool:**  
  - 1st Place: $10,000  
  - 2nd Place: $8,000  
  - 3rd Place: $7,000  
  - 4th–8th Places: $5,000 each  
- **Additional Resources:**  
  - [Kaggle Competition Overview](https://www.kaggle.com/c/march-machine-learning-mania-2025/overview)  
  - Tutorials and discussion forums on Kaggle  
  - External data sources such as KenPom, NET, Sagarin, BPI, Vegas odds, and more

## Methodology [WIP]

The project is built around the following framework:
- **Win Probability Modeling:**  
  Develop a model to compute the probability that any given team will beat any other team based on historical and external ranking data.
- **Bracket Simulation:**  
  Utilize the computed probabilities to simulate the tournament bracket. Ensure that the predicted brackets are valid by following the tournament rules (e.g., a team must win in Round 1 to advance to Round 2).
- **Optimization:**  
  Experiment with multiple models and incorporate insights from Kaggle discussion boards and previous competition submissions.
- **Experimentation:**  
  Leverage different data sources and model configurations to fine-tune predictions.

