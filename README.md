# Fifa17
This Python code demonstrates a data analysis and visualization process using the Pandas, Seaborn, and Bokeh libraries. It begins by reading a CSV file containing FIFA 2019 player data into a Pandas DataFrame named data_frame. Subsequently, a new DataFrame, df1, is created to focus on specific columns ('Name', 'Wage', 'Value'). The code then defines a function, value_to_float, to convert the 'Wage' and 'Value' columns into numeric values, handling cases where the amounts are provided in thousands (K), millions (M), or billions (B).

After applying the conversion to the 'Wage' and 'Value' columns, a new column 'difference' is calculated, representing the disparity between a player's market value and their wage. The DataFrame is sorted based on this difference in descending order. The Seaborn library is employed to generate a scatter plot visualizing the relationship between wages and values. Finally, the Bokeh library is utilized to create an interactive scatter plot with tooltips, allowing users to explore specific player details by hovering over data points. This comprehensive approach enables effective exploration and visualization of key financial aspects of FIFA 2019 players, facilitating insights into the economic dynamics within the virtual football world.
