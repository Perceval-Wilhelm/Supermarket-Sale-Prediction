
# InspireLab Technical Assessment Test for AI Fresher Position

This reposity is mainly dedicated to solving tasks and problems in the InspireLab Technical Assessment Test for the AI Fresher position.

The task is to build a regression model to predict supermarket sales based on the provided dataset.

The dataset contains information about supermarket sales across different branches. It includes various features such as the branch, city, customer type, gender, product line, unit price, quantity, and total sales. 

Supermarket Sales Dataset: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales


## Getting started

### 1. Prerequisites

- Python <=3.11
- CUDA 11.8 (if possibble or CPU is acceptable)

### 2. Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.txt file.

```bash
  pip install requirements.txt
```

### 3. Usage

- Clone the repository to your local machine.
- Ensure you have the required libraries installed (mentioned in prerequisites).
- Replace the placeholder dataset loading and model definitions in the script with your specific data and models.
- Run the [Notebook.ipynb](https://github.com/sirrtt/InspireLab-Technical-Assessment-Test-for-AI-Fresher-Position/blob/main/Notebook.ipynb) file.

## Model Used:

- Linear Regression 
- Ridge Regression
- Lasso Regression
- Stochastic Gradient Descent (SGD) Regression
- Random Forest Regression
- Neural Network

## Evaluation Metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared

## Results:

The [Notebook.ipynb](https://github.com/sirrtt/InspireLab-Technical-Assessment-Test-for-AI-Fresher-Position/blob/main/Notebook.ipynb) generates a table comparing the performance metrics (MSE, RMSE, MAE, R-squared) for each model before and after tuning. This allows to analyze the impact of tuning on the model's ability to generalize to unseen data.

## Further Exploration:

- Experiment with different hyperparameter tuning techniques (random search, keras tuner).
- Try additional machine learning/deep learning models suitable for this task.
    
## License

[MIT](https://choosealicense.com/licenses/mit/)

