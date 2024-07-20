### README File


# Customer Personality Analysis with Python

This project performs a comprehensive customer personality analysis using a dataset from a marketing campaign. The analysis involves understanding customer demographics, behavior, and responses to marketing efforts.

## Project Structure

- `Customer Personality Analysis with Python.ipynb`: Jupyter Notebook containing the complete analysis.
- `marketing_campaign.csv`: Dataset used for the analysis.
- `age_distribution.png`, `income_distribution.png`, `marital_status_distribution.png`, `education_level_distribution.png`: Visualizations generated during the analysis.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Solomon-Akintola/customer-personality-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-personality-analysis
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Customer Personality Analysis with Python.ipynb
   ```
2. Run the cells in the notebook to perform the analysis.

## Analysis Overview

### Data Preparation

- Loading and examining the dataset.
- Calculating customer age.
- Creating a total children feature.
- Handling missing values.

### Exploratory Data Analysis (EDA)

- Age distribution
- Income distribution
- Marital status distribution
- Education level distribution

### Customer Segmentation

Using KMeans clustering to segment customers based on demographics and purchasing behavior.

### Predictive Modeling

Using logistic regression to predict customer responses to marketing campaigns.

### Business Implications

- Targeted marketing
- Product development
- Customer retention
- Personalized communication

## Conclusion

This analysis provides valuable insights into customer demographics and behavior, enabling more effective marketing strategies and product development.
