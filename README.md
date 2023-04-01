# Taxi Data Bokeh Charts

In this [project](code.ipynb), I used Python to draw the following interactive bar charts and piechart with NYC taxi data for 2016 January:
1. A [bokeh bar chart](chart_results) with day of the week (Monday, Tuesday, ...) on the x-axis and the average duration of rides on the y-axis. Make sure that the hover tool is activated and that it shows the average duration when the cursor hovers over it.
2. A [bokeh interactive chart](chart_results) with a slider containing the hour of the day (0,1,...23) and the average number of rides for each hour for each day of the week. I.e., the chart should contain days of the week on the x-axis and the mean number of rides on the y-axis for a particular hour of the day. Moving the slider (e.g., from 10 to 11) should replace the chart for 1000 hrs by the chart for 1100 hrs). Don't forget the tooltip: 
   - sliders
   - vbar
   - note that column names must be strings for converting a data frame into a column data source
3. A [piechart](chart_results) that shows how much of the total payment comes from each day of the week. The pie should have seven slices, one for each day, and the size of each slice depends on the fraction it contributes to the total. Again, don't forget the tooltip.
