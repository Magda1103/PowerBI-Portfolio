# The Game Awards Analysis Project

## Project Overview
This project provides a comprehensive analysis of historical data from "The Game Awards". The main objective is to explore patterns in award nominations, analyze industry trends, and highlight major milestones in gaming history, including a focus on the 2025 cycle.

## Dashboard Preview
| Nominations Analysis | Winners Overview |
| :--- | :--- |
| <img width="1024" height="575" alt="Obrazek 3" src="https://github.com/user-attachments/assets/25971acb-0aa2-4e47-baeb-ab92a63cb24d" /> | <img width="1024" height="573" alt="Obrazek 1" src="https://github.com/user-attachments/assets/02b357cc-fd8a-4385-9534-1d6ab7c974b6" /> |

## Key Features
- **Nominations Overview:** A detailed view of total nominations and award distribution across different categories.
- **Industry Insights:** Visualizations identifying the most nominated studios and game titles.
- **Dynamic Exploration:** Interactive elements allowing users to slice data by game title, publisher, and category.

## Technologies Used
- **Power BI:** Data modeling and interactive dashboard development.
- **Power Query:** Data import, transformation, and cleaning.
- **DAX:** Custom measures implemented to track performance metrics:
    - `Nominations`: Calculated using `COUNTROWS('The Game Awards')` to determine the total number of nomination records.

## Key Insights
- **Competitive Landscape:** The analysis reveals that specific titles like *Clair Obscur: Expedition 33* and *Death Stranding 2* significantly dominate the nomination charts, indicating strong industry anticipation.
- **Publisher Impact:** By utilizing the publisher filter (e.g., Sony Interactive Entertainment), we can clearly see the distribution of nominations across major industry players, highlighting their strategic focus on key flagship titles.
<img width="1024" height="571" alt="Obrazek 4" src="https://github.com/user-attachments/assets/ea87249f-693b-4eb4-8259-b156dc572e80" />
<img width="1024" height="572" alt="Obrazek 6" src="https://github.com/user-attachments/assets/39b36cd2-9d4c-4441-ba0a-452d82b750b0" />
- **Conversion Efficiency:** The visualization of "Number of Wins" demonstrates how effectively specific titles convert their nominations into actual awards, providing a clear metric for critical acclaim.
<img width="1024" height="574" alt="Obrazek 5" src="https://github.com/user-attachments/assets/c6dc23a9-ab41-4a9a-ab96-e8df1dac514b" />
<img width="1024" height="573" alt="Obrazek 7" src="https://github.com/user-attachments/assets/9097a5ae-a971-441d-8071-252daa7425f9" />

## How to use
You can download the `TGA.pbix` file from this repository and open it in Power BI Desktop to interact with the full dashboard and explore the data yourself.
