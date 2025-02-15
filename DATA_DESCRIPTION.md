# Data Description

## Introduction  
The US Adult Census dataset consists of **48,842** entries extracted from the **1994 US Census database**.  

- In **Section 1**, we explore the data to understand demographic trends.  
- In **Section 2**, we use this understanding to build models predicting whether an individual earns more or less than **$50,000** in 1994.  
- In **Section 3**, we review existing research papers on this dataset to analyze different methods used.  
- In **Section 4**, we compare our models with other approaches to identify key features, effective methods, and the intuition behind the results.  

---

## The Dataset  
Each entry in the dataset contains the following attributes:  

### **Demographic Information**  
- **`age`**: The age of an individual (Integer > 0)  
- **`workclass`**: Employment status  
  - *Values*: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked  
- **`fnlwgt`**: Final weight (Integer > 0), representing how many people the entry represents  
- **`education`**: Highest level of education achieved  
  - *Values*: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool  
- **`education-num`**: Highest level of education achieved (numerical) (Integer > 0)  
- **`marital-status`**: Marital status  
  - *Values*: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse  
- **`relationship`**: Relationship within the household  
  - *Values*: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried  
- **`race`**: Race of an individual  
  - *Values*: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black  
- **`sex`**: Biological sex  
  - *Values*: Male, Female  
- **`native-country`**: Country of origin  
  - *Examples*: United States, Cambodia, England, Canada, Germany, India, Japan, China, Mexico, France, Thailand, etc.  

### **Employment & Financial Information**  
- **`occupation`**: General type of occupation  
  - *Values*: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Private-house-serv, Protective-serv, Armed-Forces  
- **`capital-gain`**: Capital gains (Integer ≥ 0)  
- **`capital-loss`**: Capital loss (Integer ≥ 0)  
- **`hours-per-week`**: Number of hours worked per week (Continuous)  

### **Target Variable (Label)**  
- **`income`**: Whether an individual earns more than **$50,000 annually**  
  - *Values*: `<=50K`, `>50K`  

