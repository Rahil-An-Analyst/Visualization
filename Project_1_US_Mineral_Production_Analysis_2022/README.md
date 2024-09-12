## **Interactive Data Visualization of U.S. Mineral Production (2022)**

--

## Report  
Explore the interactive dashboard here -  
https://rpubs.com/rahil1998/1219434

--

## Overview  
This project aims to improve the clarity and effectiveness of the original Visual Capitalist (2023) chart, which highlighted U.S. states that contributed most to America's mineral production value in 2022. The goal is to address the visual issues, such as difficulty ranking states, cluttered representation of Eastern states, poor color scheme, and limited interactivity, and enhance the user experience through a dynamic, interactive dashboard.

--

## Objectives  
- Improve the ranking of states by mineral production value using a ranked bar chart alongside a map.
- Provide a clean and flat U.S. map to reduce clutter and distortion, especially in Eastern states.
- Implement a more intuitive color gradient for easier rank differentiation and readability.
- Enhance user interactivity by allowing exploration of detailed mineral data, trends, and percentage contributions through tooltips.

--

## Visual Issues Addressed  
### 1. Difficulty Ranking States:  
The original visual lacked clear ranking of mineral production values.
- **Solution**: Added a ranked bar chart alongside the map to allow users to quickly identify top and bottom performers. Mineral production values are also displayed interactively in the tooltip.

--

### 2. Cluttered Eastern States:  
The original curved map distorted the Eastern U.S. states, causing difficulty in reading values and ranks.
- **Solution**: Replaced the curved map with a flat map to reduce clutter. Tooltips further enhance the readability of each state's mineral production value.

--

### 3. Poor Color Scheme:  
The color scheme of the "Top 5 States Percentage of Total" visual was hard to interpret, making it difficult to differentiate between state ranks.
- **Solution**: A better color gradient was applied to improve the distinction between ranks. The exact percentage contribution is now included in the tooltip.

--

### 4. Limited Interactivity:  
The original static visual limited exploration of deeper insights.
- **Solution**: An interactive dashboard was implemented to allow users to explore additional information dynamically. Users can now see detailed comparisons, trends, and percentage contributions.

--

## Data Description  
- **Data Source**: Mineral production data from Visual Capitalist (2023).
- **Columns Used**:
  - **State**: The U.S. state name.
  - **Production Value (in billions)**: Mineral production value for each state.
  - **Top Minerals**: Leading minerals produced in each state (gold, silver, copper, lithium, etc.).

--

## Methodology  
- **Data Visualization**: Using `echarts4r`, the project developed a map-based visual coupled with a ranked bar chart for clear comparison. 
- **Tooltip Integration**: Tooltips were integrated to provide users with mineral production values, percentage contributions, and state rankings interactively.
- **Color Scheme**: A new gradient was applied to better distinguish between different production levels across the states.

--

## Results  
Key insights from the improved visual include:
- Clear identification of the top contributors to U.S. mineral production value.
- Improved legibility of all states, including those in the Eastern U.S.
- Better representation of ranks and mineral production values through interactive tooltips and a ranked bar chart.
  
--

## How to Use  
- **Setup**: Ensure R is installed with the necessary visualization libraries (`echarts4r`, `shiny`, etc.).
- **Usage**: View the dashboard on RPubs or clone the repository to explore and modify the code locally.

--

## Files  
- `README.md`: This file.
- `Visualization - Project 1.Rmd`: The RMarkdown file used to create the interactive dashboard.
- `Visualization---Project-1.html`: The compiled HTML file for the interactive visualization.

--

## License  
This project is licensed under the MIT License.

--

## Contact  
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).
