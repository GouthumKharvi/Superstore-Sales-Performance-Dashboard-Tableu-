# Superstore-Sales-Performance-Dashboard-Tableu-
This project provides an interactive Tableau dashboard to analyze Superstore’s sales performance from 2018 to 2021. The dashboard allows users to filter data by date, segment, ship mode, and state, providing a flexible view into various sales metrics and trends.

## Solution Summary

1. **Data Preparation**:
   - Connected to the Sample Superstore dataset and created an extract for improved performance.
   - Cleaned and formatted data as needed to support visualization requirements.

2. **Dashboard Design and Layout**:
   - Configured a fixed-size dashboard (Width: 1055, Height: 850) for consistent layout and alignment.
   - Organized components into containers for structured, easy-to-navigate sections, including a title, filters, KPIs, and visualizations.
   - Used horizontal containers to group similar elements together and a vertical container to align these sections.

3. **Filters and Interactivity**:
   - Added `Order Date`, `Segment`, `Ship Mode`, and `State` filters to allow customized data exploration.
   - Configured `Order Date` as a range filter for flexible time period selection.
   - Set up actionable filters in the Pie and Bubble charts for additional interactivity, allowing users to explore data by region and sub-category dynamically.

4. **KPI Scorecards**:
   - Created scorecards for key metrics:
     - **Total Sales**: Displayed in thousands with custom color (`#76b7b2`).
     - **Total Profit**: Displayed in thousands with matching formatting.
     - **Total Volume**: Displayed as a count value.
     - **Sales Per Customer**: Computed and displayed with the same color theme.
   - Tooltips were disabled on these views to maintain focus on the metrics.

5. **Visualizations**:
   - **Pie Chart**: Showcases the percent of total sales by region, with a summer color palette and black borders. Tooltip displays region, percentage, and sales in thousands for clear comparison.
   - **Top N States Bar Chart**: Horizontal bar chart showing top states by sales, customizable with a parameter to adjust the number of states shown. Sorted in descending order with sales values labeled in dollars.
   - **Bubble Chart**: Visualizes sales by sub-category, with bubbles colored by category. Tooltip includes only the sub-category and sales in thousands for a clean look.
   - **Line Chart**: Displays monthly sales trends over time, with the X-axis formatted to show month and year (e.g., Jan 22). Tooltip includes sales in thousands for each month-year.

6. **Styling and Formatting**:
   - Applied consistent color themes across metrics and visualizations for a cohesive look.
   - Adjusted tooltips, legends, and chart borders to ensure clarity and visual appeal.
   - Positioned legends strategically next to their respective charts, avoiding overlap and keeping the layout uncluttered.

7. **Publishing and Finalization**:
   - Hidden all individual sheets for a polished final dashboard.
   - Published the dashboard to Tableau Public, making it accessible for viewing and sharing.

---

This Tableau dashboard provides an insightful analysis of Superstore's sales performance, empowering stakeholders to explore data interactively and make informed business decisions. The combination of dynamic filters, scorecards, and visualizations offers a comprehensive view of key metrics and trends.
