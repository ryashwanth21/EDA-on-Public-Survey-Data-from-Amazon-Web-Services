# Developer Survey Dataset Analysis

## Overview
This repository contains an analysis of a developer survey dataset aimed at uncovering insights into developer compensation, job satisfaction, and related factors. The project involves data cleaning, exploratory data analysis (EDA), and interactive visualizations to present findings effectively.

## Dataset
- **Source**: [Developer Survey Results](https://nkb-backend-otg-media-static.s3.ap-south-1.amazonaws.com/otg_prod/media/Tech_4.0/AI_ML/Datasets/survey_results_public.csv)
- **Description**: The dataset includes responses from developers on various topics, including compensation, job satisfaction, education, and work experience.

## Analysis Process
1. **Data Loading**:
    - The dataset is loaded using Pandas.
  
2. **Data Cleaning**:
    - Missing values are handled using KNN imputation for numerical features and mode imputation for categorical features.
  
3. **Exploratory Data Analysis (EDA)**:
    - Various visualizations are created to explore the data, including:
        - Histograms to understand the distribution of numerical variables.
        - Count plots for categorical variables.
        - Correlation matrices to examine relationships between variables.
  
4. **Interactive Visualizations**:
    - **Choropleth Map**: Displays average compensation by country.
    - **Sankey Diagram**: Illustrates the relationship between education level and employment type.
    - **Radar Chart**: Compares job satisfaction across different developer types.
  
5. **Specific Relationships**:
    - Analysis of:
        - Average work hours versus years of coding experience.
        - Job satisfaction by operating system.
        - Compensation versus work week hours.
    - Visualizations include line plots, bar charts, and scatter plots.

## Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly

## How to Run
To reproduce the analysis:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Developer_Survey_Analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Developer_Survey_Analysis
    ```
3. Install the required libraries (if not already installed):
    ```bash
    pip install -r requirements.txt
    ```
4. Open the Jupyter Notebook file (`EDA_Yash.ipynb`) and run the cells to see the analysis.

## Results
The analysis provides insights into various aspects of the developer community, highlighting trends in compensation, job satisfaction, and working conditions.

## Acknowledgments
- [Developer Survey Results](https://nkb-backend-otg-media-static.s3.ap-south-1.amazonaws.com/otg_prod/media/Tech_4.0/AI_ML/Datasets/survey_results_public.csv) for providing the data used in this analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries, please reach out at: ryashwanth2005@gmail.com.
