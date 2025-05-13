# COVID-19 Global Data Tracker

This project is a data analysis and reporting tool that tracks global COVID-19 trends, including cases, deaths, recoveries, and vaccinations. Using real-world data from [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv), the project provides insights into the pandemic's progression across countries and time.

## Objectives

The primary objectives of this project are:
- **Import and clean COVID-19 global data**: Load and preprocess the dataset for analysis.
- **Analyze time trends**: Study trends in cases, deaths, and vaccinations over time.
- **Compare metrics across countries/regions**: Focus on specific countries of interest (e.g., USA, India, Brazil).
- **Visualize trends with charts and maps**: Use visualizations to highlight key patterns and insights.
- **Communicate findings**: Present results in a well-documented Jupyter Notebook with narrative explanations.

## Tools and Libraries Used

The following tools and libraries were used in this project:
- **Python**: Programming language for data analysis and visualization.
- **pandas**: For data manipulation and cleaning.
- **matplotlib**: For creating static visualizations.
- **seaborn**: For enhanced data visualization.
- **plotly**: For interactive choropleth maps.
- **Jupyter Notebook**: For combining code, visualizations, and narrative explanations.

## How to Run/View the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Imisioluwa3/COVID-19-Global-Data-Tracker.git
   cd COVID-19-Global-Data-Tracker

2. **Download the Dataset**:
    Download the dataset from Our World in Data.
    Save the file as owid-covid-data.csv in the project directory.

3. **Install Dependencies**:
   Ensure you have Python installed, then install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn plotly jupyter
   ```

4. **Run the Notebook**: 
    Open the Jupyter Notebook:
   ```bash
   jupyter notebook "COVID 19 Tracker.ipynb"
   ```

    Follow the step-by-step analysis in the notebook.

5. **Optional Export**: 
   Export the notebook to PDF or PowerPoint for presentation:
   ```bash
   jupyter nbconvert --to pdf "COVID 19 Tracker.ipynb"
   ```

# Insights and Reflections

## Key Insights:
1. The United States, India, and Brazil have experienced significant COVID-19 case surges at different points in time.

2. Vaccination rollouts have varied widely across countries, with some achieving higher coverage earlier than others.

3. Daily new cases show clear peaks and troughs, indicating waves of infections.

4. The choropleth map highlights regions with high case densities, providing a global perspective on the pandemic's impact.

## Reflections:
This project demonstrates the power of data analysis in understanding global health crises. By leveraging Python's data tools, we can uncover trends, identify anomalies, and communicate findings effectively. The visualizations and insights generated here can inform public health strategies and raise awareness about the pandemic's ongoing challenges.