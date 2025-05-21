# 🚢 Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

## Project Overview

This project presents a comprehensive data cleaning and exploratory data analysis (EDA) of the famous Titanic dataset. The analysis aims to uncover patterns and insights about the passengers aboard the RMS Titanic and factors that influenced survival during the tragic sinking in 1912.

## Table of Contents

- [Dataset Description](#dataset-description)
- [Installation Requirements](#installation-requirements)
- [Data Cleaning Process](#data-cleaning-process)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset Description

The Titanic dataset is one of the most popular datasets in data science, containing demographics and passenger information from 891 of the 2,224 passengers and crew aboard the Titanic. The dataset includes the following variables:

| Variable | Description |
|----------|-------------|
| PassengerId | Unique identifier for each passenger |
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name | Passenger name |
| Sex | Passenger gender |
| Age | Passenger age |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Passenger fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |



## Installation Requirements

To run this project, you'll need Python 3.7+ and the following libraries:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
plotly
```


## Data Cleaning Process

The data cleaning process included the following steps:

1. **Handling Missing Values**
   - Imputation of missing ages using median values based on passenger class and gender
   - Filling missing cabin information with 'Unknown'
   - Imputing missing embarked values with the most frequent port

2. **Feature Engineering**
   - Extracting titles from passenger names
   - Creating family size feature by combining SibSp and Parch
   - Extracting deck information from cabin numbers
   - Creating age groups for better analysis

3. **Data Transformation**
   - Converting categorical variables to numerical using encoding techniques
   - Normalizing numerical features where appropriate
   - Handling outliers in fare and age distributions

## Exploratory Data Analysis

The EDA phase explores various aspects of the dataset to uncover patterns and relationships between variables:

1. **Demographic Analysis**
   - Age and gender distribution of passengers
   - Class distribution and socioeconomic factors

2. **Survival Analysis**
   - Survival rates across different passenger classes
   - Gender-based survival patterns
   - Age and survival correlation
   - Family size impact on survival chances

3. **Fare Analysis**
   - Ticket price distribution
   - Correlation between fare and class
   - Fare's relationship with survival

4. **Embarkation Analysis**
   - Passenger distribution by port of embarkation
   - Survival rates by embarkation port

## Key Insights

Some of the key findings from the analysis include:

- Women had a significantly higher survival rate than men (approximately 74% vs. 19%)
- Passengers in higher classes (1st class) had better survival chances
- Children under 10 had higher survival rates compared to other age groups
- Passengers traveling alone had lower survival rates than those with family
- Passengers who embarked at Cherbourg had the highest survival rate

## Visualizations

The project includes various visualizations to help understand the data better:

- Survival rate by passenger class
- Age distribution by gender and survival status
- Correlation heatmap of numerical variables
- Family size vs. survival rate
- Survival rate by ticket fare
- Geographical analysis of embarkation ports

## Usage

To explore this project:

1. Clone the repository
2. Install the required dependencies:
3. Run the Jupyter notebooks in sequence:

## Contributing

Contributions to this project are welcome! Please feel free to submit a pull request or open an issue if you have suggestions for improvements or additional analyses.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-analysis`)
3. Commit your changes (`git commit -m 'Add some amazing analysis'`)
4. Push to the branch (`git push origin feature/amazing-analysis`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*Note: This project is for educational purposes only. The analysis and insights are based on the available dataset and may not fully represent the historical reality of the Titanic disaster.*
