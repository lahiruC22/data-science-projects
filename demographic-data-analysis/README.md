# Demographic Data Analysis  

This project uses demographic data extracted from the 1994 Census database to answer key questions about the dataset. By leveraging Python and pandas, it provides insights into various demographic metrics, focusing on education, income, and work habits.  

## Objectives  

The analysis addresses the following questions:  
1. **Race Representation**: 
How many people of each race are represented in the dataset?  

2. **Average Age of Men**: 
What is the average age of men?  

3. **Bachelor's Degree Holders**: 
What percentage of people have a Bachelor's degree?  

4. **Income and Education**:  
   - What percentage of people with advanced education (Bachelor's, Master's, or Doctorate) earn more than 50K?  
   - What percentage of people without advanced education earn more than 50K?  

5. **Work Hours and Income**:  
   - What is the minimum number of hours a person works per week?  
   - What percentage of people working the minimum hours earn more than 50K?  

6. **Country-Based Insights**:  
   - Which country has the highest percentage of people earning >50K, and what is that percentage?  

7. **Occupation Insights**:  
   - What is the most popular occupation for people earning >50K in India?  

## Tools and Libraries Used  

- **Python**: Main programming language for the analysis.  
- **pandas**: Data manipulation and analysis.  

## Highlights  

- **No Visualizations**: The project focuses purely on data processing and computation to derive answers.  
- **Practical Insights**: Provides actionable insights about demographics, education, and income distribution.  
- **Data Exploration**: Uses pandas to query and analyze the data efficiently.  

## How to Use  

1. Clone the repository:  
   ```bash
   git clone https://github.com/lahiruC22/data-science-projects.git

2. Navigate to the project folder:
    ```bash
    cd demographic-data-analysis  

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook demographic_data.ipynb  

4. Correct the following path to load the data set.
    ```python3
    adult_data = pd.read_csv("path/to/data/set")

5. Run the notebook to explore the analysis and results.

### Dataset Information

    Source: 1994 Census database.
    Features: Includes demographic attributes like race, age, education, income, and work hours.