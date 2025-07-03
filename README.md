1. Check Data Types – Use .dtypes to see the data type of each column.
2. Check for Negative Values – Ensure there are no negative values in 'Confirmed', 'Deaths', or 'Recovered' columns.
3. Total Active Cases Calculation – Create a new 'Active' column by subtracting deaths and recovered from confirmed cases.
4. Top 10 Countries by Active Cases – Sort and display the countries with the highest active cases.
5. Visualize Active Cases – Make a bar plot showing top 10 countries with the most active cases.
6. Correlation Heatmap – Use seaborn.heatmap() to visualize correlation between numerical columns.
7. Check Countries with Zero Deaths – Filter and list countries with confirmed cases but zero deaths.
8. Deaths per 100 Confirmed Cases – Calculate and add a new column showing death rate per 100 confirmed cases.
9. Recovered per 100 Confirmed Cases – Calculate and add a new column showing recovery rate per 100 confirmed cases.
10. Sort by Death Rate – Identify countries with the highest death rates based on calculated columns
