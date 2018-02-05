"# Visualization-with-D3.js" 
dataset : https://www.kaggle.com/zynicide/wine-reviews
Data Transformation :
The data set is huge, so for transformation, following things were done:
1. Only picked US data.

2. Removed the rows empty for price/points.

3. Picked only the price, points, province, winery, designation and variety fields.

4. Listed the unique provinces and added a column for them.

5. Removed outliers with price more than 1K.

Scatter plot visualizes the wine varieties based on different provinces. The dots are colored, based on different varieties.
