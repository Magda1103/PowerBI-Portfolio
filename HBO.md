# HBO Max Content Analysis

## Project Overview
This project presents an interactive Power BI report analyzing the HBO Max content library. It provides a detailed breakdown of both movies and TV shows, focusing on performance metrics, audience ratings, and content distribution patterns.

## Dashboard Preview
| Movies Report | TV Shows Report |
| :--- | :--- |
| <img width="1024" height="573" alt="Obrazek 8" src="https://github.com/user-attachments/assets/bebd2445-e9c1-4f91-a8c8-c4e8eed1af61" />
 | <img width="1024" height="572" alt="Obrazek 9" src="https://github.com/user-attachments/assets/6248bbee-c88c-4673-8bd3-e6a1545333cc" />
 |

## Key Features
- **Dual-View Dashboard:** Seamless switching between "Movies" and "TV Shows" reports using a clean, modern navigation interface.
- **Performance Metrics:** Calculation of mean TMDB and IMDb scores, alongside total user votes.
- **Distribution Analysis:** 
    - Movies: Visualizes the distribution of runtime, helping to understand typical movie lengths.
    - TV Shows: Analyzes the number of seasons, providing insights into long-running series vs. limited-run content.
- **Global & Demographic Insights:** Filtering by Country and Age Certification to understand content origin and target audience.

## Technologies Used
- **Power BI:** Comprehensive data visualization and UI/UX design.
- **Power Query:** Data cleaning, handling missing values, and unifying formats from different sources.
- **DAX:** Utilized to create complex aggregations for the KPI cards (Mean scores, total votes, and movie counts).

## Data Model
<img width="1024" height="534" alt="Obrazek 10" src="https://github.com/user-attachments/assets/7b9ab816-f4c4-4367-be98-b755f971fd8e" />

## Key Insights
- **Production Hub:** The US is the dominant producer of films on the platform, accounting for over 83% of the total movie count.
- **Maturity Rating:** The TV shows report highlights that 'TV-MA' is the most frequent age certification, making up 55.75% of the TV show library, reflecting HBO's focus on mature content.
- **Viewer Engagement:** Popularity is highly concentrated in a few blockbuster titles like *Game of Thrones*, which significantly leads in total IMDb votes compared to other TV shows.

## How to use
You can download the `HBO.pbix` file from this repository and open it in Power BI Desktop to interact with the full dashboard and explore the content library yourself.
