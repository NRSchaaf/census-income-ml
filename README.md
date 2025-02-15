# Income Prediction using Census Data

This project applies machine learning models, specifically **Decision Tree** and **Random Forest**, to predict whether an individual’s income exceeds **$50K** per year using the **Census Income** dataset (also called **`adultsData`**).

## Dataset Overview
The dataset consists of **48,842** entries from the **1994 US Census** database. It contains various attributes that describe an individual, such as age, employment type, education, marital status, and work hours per week. The goal is to predict if an individual earns more than **$50K** annually.

## Project Tasks
1. **Data Preprocessing**
   - Drop rows with missing values.
   - Remove categorical variables with more than 32 levels.
   
2. **Data Split**
   - Split the dataset into **80%** training data and **20%** test data.

3. **Model Building**
   - Build a **Decision Tree** model on the training data and predict the outcome on the test data.
   - Calculate the accuracy of the Decision Tree model.

4. **Random Forest**
   - Build a **Random Forest** model with **50 trees** on the training data and predict the outcome on the test data.
   - Calculate the accuracy of the Random Forest model.

## Project Structure
    - **`DATA_DESCRIPTION.md`**: Contains details about the dataset and its attributes.
    - **`income_prediction.ipynb`**: Jupyter notebook containing data preprocessing, model building, and evaluation steps.
    - **`requirements.txt`**: List of Python dependencies required to run the project.


## Prerequisites
To run the project, you need the following Python libraries:
- `pandas`
- `numpy`
- `sklearn`
- `matplotlib`
- `seaborn`

You can install them using:
`bash`
`pip install -r requirements.txt`


## How to Run
1. Clone the repository to your local machine.
2. Open the Jupyter notebook `income_prediction.ipynb`.
3. Follow the instructions inside the notebook to execute the steps.


## License
This project is open-source and available under the MIT License.
