# HW4-Network
Visualization of data that is one-to-many. Visualizing the passing sequences started by Jimmy Butler in game 5 of the NBA finals. All data was recorded myself.

The jupyter notebook contains two ways to visualize data. The last cell will create a Dash rendering that includes hypothesis and other text explanations. However, there is an issue with Dash and Plotly's Sankey that does not allow the custom data on hover to be displayed as I wanted. This custom data is shown in the sankey contained in fig2. 

Having more data would remove the problem of small sample size contained in the table and give true insight. However, as the size of the data increases, so does the complexity of the sankey. As the number of combinations of passes increases, the interpretability of the sankey goes down. Limiting the sankey to show passing sequences that have happened more than n times could help this somewhat.
