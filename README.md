Check Data Types – Use .dtypes to see the data type of each column.
Check for Negative Values – Ensure there are no negative values in 'Confirmed', 'Deaths', or 'Recovered' columns.
Total Active Cases Calculation – Create a new 'Active' column by subtracting deaths and recovered from confirmed cases.
Top 10 Countries by Active Cases – Sort and display the countries with the highest active cases.
Visualize Active Cases – Make a bar plot showing top 10 countries with the most active cases.
Correlation Heatmap – Use seaborn.heatmap() to visualize correlation between numerical columns.
Check Countries with Zero Deaths – Filter and list countries with confirmed cases but zero deaths.
Deaths per 100 Confirmed Cases – Calculate and add a new column showing death rate per 100 confirmed cases.
Recovered per 100 Confirmed Cases – Calculate and add a new column showing recovery rate per 100 confirmed cases.
Sort by Death Rate – Identify countries with the highest death rates based on calculated columns
