# NEO Hazard Prediction: A Machine Learning Approach

This project explores the use of machine learning to predict the hazard status of Near Earth Objects (NEOs).

## Project Overview

- **Goal:** Develop a classification model that can accurately predict whether a Near Earth Object poses a potential threat to Earth.
- **Dataset:** The dataset contains information about a collection of NEOs, including their absolute magnitude, estimated diameter, relative velocity, and other characteristics.
- **Methods:**
  - **Data Preprocessing:** Feature engineering, handling missing values, and data scaling.
  - **Model Selection:** Decision Tree and AdaBoost.
  - **Evaluation:** Stratified K-Fold cross-validation, F1-score, accuracy, precision, recall, ROC AUC.
  - **Feature Importance Analysis:** Examining the influence of different features on the model's predictions.
  - **Visualization:** Using plots to visualize the data, model performance, and key findings.

## Project Structure

```
├── nearest-earth-objects(1910-2024).csv  # The dataset file
└── NEO_Hazard_Prediction.ipynb  # Jupyter Notebook containing code and analysis
```

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/NEO-Hazard-Prediction.git
   ```

2. **Run the notebook:**
   - Open `NEO_Hazard_Prediction.ipynb` in your Jupyter Notebook environment.
   - Execute the code cells to perform the analysis and visualize the results.

## Key Findings

- The **absolute magnitude** of the NEO is a highly influential factor in determining hazard status.
- The model struggles with **false negatives**, which could have significant consequences.
- **Further analysis** is needed to identify other factors influencing hazard and to improve the model's accuracy.

## Potential Improvements

- **Data Augmentation:** Explore techniques to balance the imbalanced dataset.
- **Feature Engineering:** Investigate additional features and potential interactions.
- **Model Exploration:** Experiment with different models and hyperparameters.
- **Ensemble Methods:** Utilize other ensemble techniques to enhance prediction accuracy.

## Contributions

Contributions are welcome! Feel free to fork this repository and submit pull requests for improvements or enhancements.

## Acknowledgements

This project was inspired by the following resources:

- [NASA Near Earth Object Program](https://cneos.jpl.nasa.gov/ca/)
- [Kaggle Dataset](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024)
