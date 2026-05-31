# Disney Movies Analysis Project

## Project Overview
This project provides an in-depth analysis of Disney movies. The primary goal was to visualize financial performance, understand the impact of inflation on gross revenue, and organize movie titles dynamically for better reporting.

## Key Features
- **Financial Performance Dashboard:** Tracks total gross revenue versus inflation-adjusted gross revenue.
- **Dynamic Content Explorer:** Allows users to view movie titles with release years appended for better clarity.
- **Metrics Summary:** Provides key figures on total production volume and financial success.

## Technologies Used
- **Power BI:** Data visualization and dashboard development.
- **Power Query:** Data transformation and cleaning.
- **DAX:** Implemented key custom measures to provide financial insights:
    - `Total Adjusted Revenue`: Sum of the inflation-adjusted gross revenue.
    - `Total revenue`: Sum of the total gross revenue.
    - `Diff`: Calculates the gap between inflation-adjusted gross and total gross.
    - `Number of movies`: Counts the total number of movie titles in the dataset.
    - `Distinct Movie Title`: A dynamic measure using `ALLEXCEPT` to ensure that titles are unique, appending the release year when duplicate names exist.
      
<img width="1024" height="572" alt="Obrazek" src="https://github.com/user-attachments/assets/2c97f5d5-86af-4846-a70d-26118007a8a3" />

## Key Insights
- The `Diff` measure highlights how inflation significantly affects the perception of a movie's financial success over time.
- The dynamic `Distinct Movie Title` measure effectively handles data ambiguity in historical records.

## How to use
You can view the project by downloading the `Disney.pbix` file and opening it in Power BI Desktop.
