## **About Me**
### Hello, I'm Alice
My journey into the data world started as an apprentice with a love for maths. As my career has grown, I enjoy applying mathemtical skills to real life scenarios.
### Education
I have completed a Level 4 Data Analyst Apprenticeship and currently working towards my Data Science Degree. 



## **Projects**
### Average USA House Prices

#### Executive Summary 
Hypothesis: the price of the homes will be higher when the square foot living space is larger.
#### Data Infrastructure & Tools
A public dataset from Kaggle has details on the sale of houses from the top 50 populated cities in the US. The data has details of the location of the property, the price, the number of beds and bathrooms. The data has been collected from different sources. There dataset does not specify when what year(s) the data was from which limits the understanding of the data as if it is based on old house prices it would not provide an accurate reflection of the current house prices.
The outcome of this data project will be available on a GitHub portfolio (link to be included)
#### Data Engineering
The square foot has a large range of values from 2 to 74340. Considering the context of the data this would show there are some data quality issues as the likelihood of the living space being 2 square foot is low. Due the large variation of the data, I added a new column to power BI table to round the living space areas to the nearest hundred which helped group the data together when producing the visualisations.
#### Data Visualisation & Dashboards
The data from Kaggle was copied to Power BI to create the visualisations. A scatter graph was produced using the new square foot column and the price of the houses, due to the volume of data an additional scatter graph was created using the average price of homes for each square foot interval. As the majority of properties fell under 10000 square foot the graphs will filtered to only include these data points as there were few points outside of this range which had an  impact on the interpretability of the graphs.




