# Employee Data Analysis Project

Welcome to the Employee Data Analysis Project! This project is a comprehensive exploration of a dataset from ABC Company, aimed at deriving valuable insights into the employee data through preprocessing, analysis, and visualization. Below, you'll find an overview of the project components, methodologies, and findings.

## Project Objective
To preprocess and analyze the given employee dataset, present the findings graphically, and derive meaningful insights to help better understand the company’s workforce.

## Dataset
The dataset contains **458 rows** and **9 columns** and includes information about employees across various teams and positions. The columns include:
- `Team`
- `Position`
- `Age`
- `Salary`
- `Height`
- `Name`
- `Number`
- `Weight`
- `College`

## Preprocessing Steps
1. **Handling Missing Data**:
   - Missing values in the `Salary` column were replaced with the **median salary**.
   - Missing values in the `College` column were replaced with the **most frequent value (mode)**.
2. **Data Correction**:
   - Randomly replaced inconsistent values in the `Height` column with values between **150 cm and 180 cm**, using `np.random.seed(42)` for reproducibility.
3. **Data Cleaning**:
   - Verified the dataset for duplicates and null values after preprocessing.
4. **Export**:
   - Saved the cleaned dataset as `cleaned_data.csv` for further analysis.

## Analysis Tasks
1. **Distribution of Employees Across Teams**:
   - Calculated the percentage split of employees across teams.
   - Visualized the distribution using a **pie chart**.

2. **Employee Segregation by Position**:
   - Grouped employees based on their positions.
   - Visualized the counts using a **horizontal bar chart**.

3. **Predominant Age Group**:
   - Identified the most frequent age group among employees.
   - Presented the data using a **histogram**.

4. **Salary Expenditure Analysis**:
   - Determined which team and position had the highest total salary expenditure.
   - Visualized the data using a **stacked bar chart**.

5. **Correlation Between Age and Salary**:
   - Computed the correlation coefficient to identify relationships.
   - Represented the data using a **scatter plot**.

## Visualizations
The project includes the following visualizations:
1. **Pie Chart**: Employee distribution across teams.
2. **Bar Chart**: Number of employees in each position.
3. **Histogram**: Predominant age group.
4. **Stacked Bar Chart**: Salary expenditure by team and position.
5. **Scatter Plot**: Age vs. Salary correlation.

## Key Findings
- The team with the highest salary expenditure is **[Team Name]**, and the position contributing most to this expenditure is **[Position Name]**.
- The most predominant age group among employees is **[Age Group]**.
- There is a **[weak/moderate/strong] correlation** between age and salary, indicating **[specific insight, e.g., older employees tend to earn more/less].**

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <github.com/Athul64/Exploratory-Data-Analysis>
   ```
2. Install the required Python libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Exploratory Data Analysis.ipynb
   ```

## Files in the Repository
- `Exploratory Data Analysis.ipynb`: The main Jupyter Notebook containing code and analysis.
- `data.csv`: The original dataset.
- `cleaned_data.csv`: The preprocessed dataset.
- `README.md`: Project overview and instructions.

## Tools Used
- **Python Libraries**:
  - `numpy` for data manipulation
  - `pandas` for data analysis
  - `matplotlib` and `seaborn` for visualizations

## Future Improvements
- Enhance visualizations by adding interactive plots using `plotly` or `dash`.
- Perform advanced statistical analysis to uncover deeper insights.
- Automate the preprocessing and analysis steps for scalability.

## License
This project is licensed under the [MIT License](LICENSE).

---

If you have any questions or feedback, feel free to raise an issue or reach out. Thank you for exploring this project!
