## **Interactive Data Visualization of U.S. Mineral Production (2022)**

## Dashboard  
Explore the interactive dashboard here -  
https://rpubs.com/rahil1998/1219448

## Overview  
This project aims to incorporate more information and improve interactivity compared to the simple visual of project 1.

## Data Description  
**Data Sources**:

USGS1 (U.S. Geological Survey) (2023). *MINERAL COMMODITY SUMMARIES 2023*, USGS Publications Repository Website, accessed 27 April 2023. https://pubs.usgs.gov/periodicals/mcs2023/mcs2023.pdf, pages 10-11, *Table 3.—Value of Non-fuel Mineral Production in the United States and Principal Non-fuel Mineral Commodities Produced in 2022*

USGS2 (U.S. Geological Survey) (2023). *MINERAL COMMODITY SUMMARIES 2023*, USGS Publications Repository Website, accessed 4th June 2023. https://pubs.usgs.gov/periodicals/mcs2023/mcs2023.pdf, page 9, *Table 1.—U.S. Mineral Industry Trends*

USGS3 (U.S. Geological Survey) (2023). *MINERAL COMMODITY SUMMARIES 2023*, USGS Publications Repository Website, accessed 4th June 2023. https://pubs.usgs.gov/periodicals/mcs2023/mcs2023.pdf, page 7, *Figure 2.—2022 U.S. Net Import Reliance*

USGS (U.S. Geological Survey) (2019). *MINERAL COMMODITY SUMMARIES 2019*, USGS Publications Repository Website, accessed 4th June 2023. https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/atoms/files/mcs2019_all.pdf, pages 10-11, *TABLE 3.—VALUE OF NONFUEL MINERAL PRODUCTION IN THE UNITED STATES AND PRINCIPAL NONFUEL MINERALS PRODUCED IN 2018*

## Methodology  
- **Data Visualization**: Using `Flexdashboard` for dashboarding, `echarts4r` and `mapview` for charts and maps, the project developed a map-based visual coupled with a ranked bar chart for clear comparison. 
- **Tooltip Integration**: Tooltips were integrated to provide users with mineral production values, percentage contributions, and state rankings interactively.

## How to Use  
- **Setup**: Ensure R is installed with the necessary visualization libraries (`echarts4r`, `shiny`, etc.).
- **Usage**: View the dashboard on RPubs or clone the repository to explore and modify the code locally.

## Files  
- `README.md`: This file.
- `Visualization - Project 2.Rmd`: The RMarkdown file used to create the interactive dashboard.
- `Visualization-Project-2.html`: The compiled HTML file for the interactive visualization.

## License  
This project is licensed under the MIT License.

## Contact  
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).
