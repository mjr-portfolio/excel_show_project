Project Title - NYC Bus Breakdown and Delay Analysis: Understanding the Key Factors Behind Transit Disruptions

----------------------------------------------------------------------------------------------------------------------------------------

Project Description - This project analyzes the causes and patterns behind bus delays and breakdowns across New York City. By exploring multiple factors such as bus company, borough, routes, and causal variations, I identified key drivers of delays and breakdowns recommending strategies for improving public transit efficiency.

----------------------------------------------------------------------------------------------------------------------------------------

Motivation - The NYC transit system is essential for millions of daily commuters. Understanding the causes of delays and breakdowns can lead to better planning, efficient resource allocation, and improved service. This project focuses on uncovering the factors behind delays and breakdowns in the city's bus system, ultimately aiming to contribute to a smoother, more reliable public transportation experience.

----------------------------------------------------------------------------------------------------------------------------------------

Data Source - The dataset was sourced from the NYC Open Data - Bus Breakdown & Delays (DOE) (https://data.cityofnewyork.us/Transportation/Bus-Breakdown-and-Delays/ez4e-fazm/about_data), containing detailed records of bus delays and breakdowns by route, bus company, borough, and weather conditions.

----------------------------------------------------------------------------------------------------------------------------------------

Questions Answered / Objectives - The main questions explored in this project were:

1. What are the most common reasons for delays and breakdowns?
2. How do delay times vary by bus company and borough?
3. Is there a correlation between specific days of the week and the frequency of breakdowns or delays?
4. Are certain bus routes more prone to delays or breakdowns than others?
5. How do breakdowns or delays vary across different seasons?

----------------------------------------------------------------------------------------------------------------------------------------

Methodology - To answer the questions, I followed these steps: - Data Preprocessing: Cleaned the dataset by handling missing values, outliers, and converting time-related columns into usable formats. - Exploratory Data Analysis (EDA): Used descriptive statistics, group-by operations, and visualizations (e.g., bar charts, heatmaps) to identify patterns. - Statistical Analysis: Applied forecasting and hypothesis testing to determine if certain factors significantly influenced delays and breakdowns.

----------------------------------------------------------------------------------------------------------------------------------------

Results & Insights -

What are the most common reasons for delays and breakdowns?

![Screenshot 2025-03-31 143654](https://github.com/user-attachments/assets/79c76598-d47e-4027-b247-7a95dec039e8)

    The top reasons for delays include Heavy Traffic (67%), Other (19%), and Mechanical Problems (5%).
    
    Mechanical Problems were the leading cause of breakdowns, accounting for 57% of all incidents,
    followed by Won't Start (16%), Flat Tire (14%), and Other (9%).

How do delay times vary by bus company and borough?

![Screenshot 2025-03-31 143714](https://github.com/user-attachments/assets/7e875496-4840-48ac-b33e-b26f4237b2cd)

    Bus Companies: Selby Transportation, Little Linda Bus Co, and Pride Transportation rank among the
                   higest average delays among all of the Bus Companies, ranging from 70 - 60 minute
                   delays respectively.
                   
    Boroughs: The Buroughs with the largest average delays aligns with those with the highest
              concentration of people, with the top 3 including Manhattan and Queens. Both of which
              offering over 40 minute average delays.

Is there a correlation between specific days of the week and the frequency of breakdowns or delays?

![Screenshot 2025-03-31 143735](https://github.com/user-attachments/assets/ac00e093-f316-446e-8d59-2246642db020)

    Delays were more frequent on Mondays, with a large reduction on Fridays. While Fridays are likely
    seeing a reduced number of delays due to fewer people commuting to work, Mondays are more abstract
    and require further information to properly understand.
    
    Breakdown frequency follows the same pattern as the delays, however less severe. The increase at
    the beginning of the week may suggest a need for maintenance to be scheduled over the weekends in
    preperation for the week ahead.

Are certain bus routes more prone to delays or breakdowns than others?

![Screenshot 2025-03-31 143753](https://github.com/user-attachments/assets/7183666c-d7b1-46f7-a9af-8d14f51c9ad9)

    Delays: The top 3 routes ('2', '1', '3') are mostly covered by the GVC LTD company. This is
            interesting due to the fact that they are not listed among the top 10 companies for delays
            as covered earlier. The Bronx Borough also is the focus for these routes.
            
    Breakdowns: 80% of the top routes for breakdowns cover the Bronx Borough, focusing our attention on
                the need to evaluate the issues in this area that seem to be more pervasive than other
                areas of the city.

How do breakdowns or delays vary across different seasons?

![Screenshot 2025-03-31 143814](https://github.com/user-attachments/assets/79e3a3d7-3184-4aa5-8ca5-c64578e7e3de)

    Delays: There is a large spike at the start of the School Year in the Autumn, with a sharp decline
            before evening out through Winter into the Spring, followed by a decline into the Summer.
            
    Breakdowns: In an almost identical fashion to the delays, breakdowns follow the exact same trend
                through the year and could be related to each other.

----------------------------------------------------------------------------------------------------------------------------------------

Key Visualizations - 

----------------------------------------------------------------------------------------------------------------------------------------

Technologies & Tools - 

----------------------------------------------------------------------------------------------------------------------------------------

Future Improvements - 

Future improvements could involve:

    
