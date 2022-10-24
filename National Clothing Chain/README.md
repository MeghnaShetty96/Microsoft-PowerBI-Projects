# National CLothing Chain
An online national clothing chain needs help in creating a targeted marketing campaign. Sales have been flat and they want to lure lost customers back. They want to advertise specific products to specific customers in specific locations, but they don’t know who to target. They have three products in mind:

Shirt: $25

Sweater: $100

Leather Bag: $1,000

# Analysis Questions:

What is the correlation (R2 value) between sales and income?

What is the correlation (R2 value) between customer ratings and product return rate?

What are the linear regression formulas to predict customer income from customer sales?

Which customer do you predict has the highest income?

Which product will be advertised the most?

Below mentioned tabs demonstrate market analysis to support the determination of the best product to the customers along with answering the above questions.

# Report Tab1

The scatterplot shows an upward positive correlation between average household income by state and average 6 months sales by state, along with which currency formatting has also been applied. The scatter plot with trendline and correlation coefficient quick measure (on a card) is used to perform a regression analysis of the relationship between average household income by state and average 6 months sales by state.

The heatmap is used to visualize income household income distribution across the US and it indicates a concentration of high income around Washington D.C. and the Northeast NY/Boston area.

![picture1](./Pictures/Report%20Tab1.png)

# Report Tab2

The scatterplot shows a downward sloping negative correlation between customer ratings and product return rate.

The horizontal bar chart indicates the maximum predicted income by customers.

![picture2](./Pictures/Report%20Tab2.png)

# Report Tab3 

Linear regression has been used to predict customer income based on sales and income of the state.The histogram shows the distribution and shape of predicted income by category and is created using a column chart and DAX formula to define the ranges/bins of the columns.

The product recommendations are defined using a DAX formula and a stacked column chart is used to display the same. The scatterplot between income and sales is upward sloping and helps in supporting cross filtering.

![picture3](./Pictures/Report%20Tab3.png)

# Report Tab4

The decomposition tree breaks down the population in every US state with respect to Industry and Predicted Income. 

![picture4](./Pictures/Report%20Tab4.png)
