# Smart City Potential Analysis Project

## Project Overview
This project analyzes urban and demographic data to assess the *Smart City Potential* across various cities worldwide. The core focus is to evaluate cities based on population metrics, capital status, and an aggregated smart city score using Python for data analysis and Power BI for interactive visualizations.

## Data Analysis (Python)
- Used Python libraries such as `pandas`, `numpy`, and `matplotlib` for data loading, cleaning, and exploratory analysis.
- Calculated key metrics including:
  - Population group classification based on city size.
  - Smart city potential score combining population rank and capital status.
  - Aggregations such as sum and average of population and smart city scores by city groups.
- Output a cleaned CSV file `smart_city_analysis_data.csv` with the following columns:
  - `city`, `capital`, `country`, `population`, `population_group`, `smart_city_score`, `lat`, `lng`, etc.
- Python scripts contain modular code for:
  - ETL processes to transform raw data.
  - Generating new features for analysis.
  - Exporting ready datasets for Power BI import.

## Power BI Dashboard
- Connected the processed CSV dataset to Power BI for advanced visualization.
- Implemented visuals such as:
  - **Bubble Map** plotting cities by geographic coordinates sized by population and colored by capital type.
  - **Clustered Column and Bar Charts** showing population and smart city score aggregates by population groups, capital status, and country.
  - **Line Chart** with dual axes to visualize trends of average smart city score and population counts.
  - **Small Multiples** for granular comparison across countries and capital statuses.
  - **KPIs** highlighting total population and average smart city readiness scores with benchmark targets.
- Configured interactive slicers for population groups, countries, and capital types to enhance exploratory analysis.
- Applied tooltips extensively, showing city-level details on hover including population, score, and administrative status.
- Dynamic titles, legends, and color coding make the dashboard user-friendly and insightful.

## How to Use
1. Clone or download the project repository.
2. Run Python scripts to clean and preprocess raw city data, creating the CSV analysis file.
3. Open Power BI Desktop and import `smart_city_analysis_data.csv`.
4. Use provided Power BI report templates or recreate visuals following the column mappings:
   - Location: `lat`, `lng`
   - Size: `population`
   - Legend/Color: `capital`, `population_group`
   - Value axes: aggregate functions on `population` and `smart_city_score`
5. Use slicers and filters to analyze specific regions or city categories.
6. Explore detailed tooltips for individual city insights.

## Project Highlights
- Integration of Python data processing and Power BI reporting offers a robust, end-to-end solution.
- Focused on actionable insights to identify cities with highest smart city potential.
- Modular scripts and clear visual mappings allow scalability and customization.

## Prerequisites
- Python 3.X with `pandas`, `numpy`, `matplotlib`
- Power BI Desktop latest version
- Basic knowledge of Power BI report building and DAX formulas

## Contact
For questions or contributions, please contact Pranay Pinjarkar at pinjarkarpranay1@gmail.com.


## Contact
For questions or contributions, please contact [Your Name] at [Your Email].
