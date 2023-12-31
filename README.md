# School Bus Delay Analysis for NYC (2023-2024)

School bus delays have become a pressing concern for parents, schools, and the Department of Education (DOE) in New York City (NYC). These delays can disrupt students' schedules, negatively impact their academic performance, and overall well-being. In response to these concerns, the DOE has requested an investigation to further understand the causes of these bus delays. This report aims to identify the challenges faced by school buses in NYC, specifically focusing on the current school year (2023-2024) and encompassing all five boroughs: Manhattan, Brooklyn, The Bronx, Queens, and Staten Island. By analyzing current data, the goal is to uncover prevalent delay trends and underlying issues that need to be addressed.
## Data 
The data used for this analysis was obtained from NYC Open Data and provided by the DOE. The dataset covers school bus breakdowns and delays. Each row represents a report made using information given by bus staff who have encountered problems during their scheduled route. The types of data included in the untouched dataset are qualitative/categorical (e.g., reasons for delay, borough), quantitative/numerical (e.g., number of students on the bus, length of delay), date and time data (e.g., occurred date, informed date), and booleans (e.g., notification statuses).

## Tools
SQL was used to trim down the original dataset to a usable file. The file was then imported into Google Sheets for further cleaning. The clean data was then imported into Tableau to create visualizations. 
## Key Insights
- Delays are typically over 15 minutes, with less than 10% of delays being between 0-15 minutes.
- Heavy traffic is the leading cause of school bus delays, accounting for over 62% of delays.
- Morning delays are significantly more frequent than afternoon delays, with 84% of delays occurring in the morning.
- Brooklyn has the highest number of school bus delays, followed by Queens, the Bronx, Manhattan, and Staten Island.
- Of all routes, route 2 in the Bronx has the most delays.
- Boro Transit Inc. and Pride Transportation have significantly higher rates of mechanical delays compared to other companies. They had 449 and 385 mechanical delays, respectively, which is over twice as many as any other company.

## Recommendations
- Optimize bus routes with frequent delays, with priority for morning routes, and explore innovative solutions like real-time traffic monitoring.
- Communicate with unreliable contractors about repeated issues, consider alternative companies, and ensure regular maintenance.
- Depending on the DOE’s priorities, addressing the delays could start with all boroughs at a time by looking at the top 3 delayed routes or the borough with the most delays, Brooklyn.

## Areas of Concern for Future Analysis
- Clarify the "Other" reason for delays through surveys and include extra space for specifying reasons in future reports.
- This dataset is regularly updated, it would be ideal to conduct regular check-ups to identify emerging trends and challenges as well as check the progress of suggested solutions.

