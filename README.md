# COVID Vaccination Analysis

This repository contains code for analyzing COVID-19 vaccination data from a dataset encompassing vaccination statistics across various countries worldwide. The analysis includes generating visualizations to understand the distribution and trends of vaccination efforts.

## Dataset
The dataset used for this analysis contains comprehensive information on COVID-19 vaccinations across different countries. It includes metrics such as total vaccinations, total vaccinations per 100 people, daily vaccinations, and more.

## Analysis Overview
The analysis comprises several visualizations aimed at providing insights into the vaccination efforts globally. Here's a brief overview of the analysis:

1. **Total Vaccination Per 100 and Daily Vaccination Per 100 Graphs for Specific Countries**: Plots graphs illustrating total vaccination per 100 people and daily vaccination per 100 people for selected countries, namely China, USA, and India.

2. **Top 10 Countries with Maximum Vaccination Per 100**: Identifies the top 10 countries with the highest total vaccination per 100 people. Countries are sorted based on total vaccinations, and the top 10 are selected for visualization.

3. **Countries with the Most Vaccinated People**: Groups the data by country and sorts it according to total vaccinations to identify countries with the highest total vaccinated individuals.

4. **Relationship Between Vaccines and Total Vaccinations**: Groups the data by vaccine type, sorts it based on total vaccinations, selects the top 10 vaccines, resets the index to country, and plots the relationship between vaccines and total vaccinations with country as hue.

5. **Choropleth Map for Total Vaccinations Per 100**: Generates a choropleth map illustrating the total vaccinations per 100 people across different countries, providing a geographical perspective of vaccination rates.

## How to Use
To replicate or further explore the analysis:

1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed (details provided in `requirements.txt`).
3. Run the main script or Jupyter notebook to execute the analysis.
4. Explore the generated visualizations to gain insights into COVID-19 vaccination trends globally.

## Dependencies
The code relies on the following Python libraries:
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Geopandas

You can install these dependencies using pip with the following command:
```
pip install -r requirements.txt
```

Happy analyzing! 📊💉
