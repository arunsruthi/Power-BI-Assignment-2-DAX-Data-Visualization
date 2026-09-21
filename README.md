https://drive.google.com/drive/folders/1-GVrTFxHR30r8RcfB00A3XJZxervAY-s?usp=drive_link
# Power-BI-Assignment-2-DAX-Data-Visualization<BR>
<B><ins>DAX</ins> (Data Analysis Expressions) is the core formula language that drives analytical power in Microsoft Power BI. It allows you to build custom calculations, build relational connections, and extract deep business insights from your raw data tables.<BR>
<ins>Measures (Dynamic Calculations)</ins>: These are calculated on the fly at query time based on user interactions like slicers, filters, or visual selections. They do not consume disk storage space and represent roughly 95% of practical DAX usage. Example: Calculating total dynamic revenue.<BR><ins>Calculated Columns</ins> (Static Rows): These add a physical new column to an existing table in your model. The calculations are evaluated during data refresh and stored statically in the file, which increases model size. Example: Concatenating [First Name] and [Last Name].<BR><ins>Calculated Tables</ins>: DAX formulas that generate an entirely new table based on existing data. Example: Creating a dedicated date/calendar table using CALENDARAUTO()
<ins>Aggregations</ins><BR>
Aggregates a single column into a scalar value.SUM(), AVERAGE(), DISTINCTCOUNT()<BR>
<ins>Iterator Functions </ins>("X" Functions)::Steps inside a table to perform row-by-row math, then aggregates the final result.SUMX(), AVERAGEX(), RANKX()Context ModifiersAlters or overwrites the active filters on a visual.CALCULATE(), ALL()>BR><BR>
<ins>Time IntelligenceCalculates trends</ins>, YTD, or rolling periods against a date table.TOTALYTD(), SAMEPERIODLASTYEAR()<br>
<ins>Trend & Category Comparisons</ins>
These are the foundational workhorses of any business report, designed to track time-based performance or rank multiple items side-by-side.<br>
<ins>Bar & Column Charts</ins>: Used to quickly compare discrete groups. Standard practice recommends vertical 
column charts for time periods and horizontal bar charts when category names are long.<br>
<ins>Line & Area Charts</ins>: Ideal for displaying continuous data and tracking trends or seasonality over time.<br>

<ins>Pie & Donut Charts</ins>: Best reserved for a very small number of categories (2 to 5 max) to show percentage market shares or structural distributions. Native customisation supports centering summary numbers directly inside the donut hole.<br>
<ins>Treemaps</ins>: Renders hierarchical or categorized data as a series of nested, proportional rectangles. A larger, darker rectangle represents a higher metric weight.<br>

<ins>Funnel Charts</ins>: Visualises sequential, linear processes. They are the go-to choice for mapping sales pipeline progression and user conversion stages.<br>

<ins>Tables & Matrices</ins>: Essential for deep analytical deep-dives. While a standard Table displays flat, multi-column row data, a Matrix operates like a dynamic pivot table. It aggregates dimensions across both columns and rows and supports cross-row collapsing/freezing

