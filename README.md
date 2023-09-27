# Final-Project-Tableau

## Project/Goals
<n> <b>  What is AIRBNB? </b>  </n>

Airbnb is a leading platform where people can book beds, apartments, and homes around the world. It allows the hosts to rent out their places at their convenience.Through Airbnb, people can find places to stay even in areas where there is a likelihood of fewer hotels.

<n> <b>  Project Goals </b>  </n>

1, Study the Airbnb data for New York City

2, Visualize how the Prices and ratings vary across different neighborhoods

3, How do the categories and other different variables influence the price and ratings?

4, How can we represent the available data in a meaningful pattern

5, How useful insights could be derived from the data


## Process
### STEP 1:
    Download the dataset from the given drive (the link was provided in the GIT repository)
### STEP 2:
    Try to understand the relation between the features and average price, by virtualizing each feature and average price.
### STEP 3:
    Carried out Analysis and plotted visuals on the following:

	    - Neighborhoods that have steady growth levels based on average price

 	    - Neighborhoods constant growth based on average price by the property type

	    - Maximum number of reviews varied based on the price ranges

	    - Relation between the average price of the properties and the number of hosts (by neighborhood)

	    - Percentage share - property types by room types

	    - Different correlations derived using Host Type

	    - Clustering & Forecasting – Model results

## Results
I selected to perform Option 2 using the Airbnb dataset to plot the visuals and perform EDA and derive meaningful insights and outcome. Based on the above analysis mentioned, I formulated the following questions for which i have answered in my Tableau visualizations for which I have attached a PDF file with all the dashboards containing my Tableau Visuals.

<n> <b> 1. Which are the neighborhoods that show a steady growth level among the given ones based on the Average Price ?</b>  </n>

Bronx was showing higher growth and later became steady as compared to Staten Island. Staten Island which had a steep growth in 2012, unfortunately dropped in 2013, though it picked up again in 2014 and slashed down again in 2015 among all the neighborhoods, which means this neighborhood was pretty unstable.

While Queens and Brooklyn have a steady growth in the average price in the neighborhood, neither they had a huge raise nor a steep fall making them a steady neighborhood amongst others. However Manhattan had a good start based on the average price but had several fluctuations and the average price reduced by 2015.

<n> <b> 2. Which are the neighborhoods that are having a constant growth based on Average price by the property type ?</b>  </n>

When we look at the average price by property in the given neighborhoods, Bronx has a steady average price values only for the apartment and house property type with a good increase in the average price of houses in 2012 Q4. But Manhattan, Queens and Brooklyn has a steady presence in all the property types from 2008- 2012 and their average price remains to be consistent.

Hence Manhattan, Brooklyn and Queens are the better neighborhoods followed by Bronx.

<n> <b> 3. How does maximum number of reviews for the properties vary based on the price ranges ?</b>  </n> 

We notice that the minimum price range for Airbnb properties starts at 366$, for this affordable range of price, there are maximum number
of reviews. We note that with increase in the price, the number of reviews decreases. However there is increase in the number of reviews again in the price bin of 700$. However for other price ranges, there are very few reviews that could be noticed. 

Also, there are reviews for certain zipcodes, which makes it evident that people prefer to choose only properties from few zipcodes. 
We have proper review ratings only for those properties with price range bins of 300- 700$. People staying on the properties within 
the mentioned price range has shown interest in providing reviews ratings compared to other who pay more price for their stay.

<n> <b> 4. Is there a correlation between the average price of the properties by neighborhood and the no.of hosts those get enrolled ?</b> </n> 

Yes, we do see a steady increase in the number of hosts from 2008 to 2014. Starting with 38 customers in 2008 to 7000+ hosts in 2014.
This has been a critical factor that has influenced the average price throughout each neighborhood. We do see a steady growth in the average price
at the neighborhood level for Manhattan, Bronx and Staten Island with increase in the host numbers.

<n> <b> 5. What are the different correlations using the Host Type ?</b> </n> 

From the Host analysis dashboard it is evident and clear that only few of the hosts have more listings (on an average of 30 listings).
But on an average we see hosts with 10-15 listings as well. From the host analysis graphs, we see that for Manhattan & Brooklyn till 2014, there 
has been a steady increase in the host numbers. Followed by Queens. 

From the graph using number of beds to the hosts, it is very clear that most of the hosts are in the range of 10- 15 Beds on an average.

<n> <b> 6. What is the Percentage share for different property types by room types ?</b> </n> 

It is very evident from the listings by room type  that entire home/ apartment has more / highest share among other different room types, followed
by private room at the next level. Though entire home/ apartments scores more share, the percentage of entire houses preferred varies from one neighborhood to another. Also when considering neighborhood like Brooklyn 90% of people prefer apartment types for staying. They do not much prefer to be in shared room space though it is a costlier neighborhood.

Only 69% of people prefer shared room accomodation out of which majority prefers apartments and only 2.75% in Bed & Breakfast. However percentage of people preferring private room is 1.10% in the Bed & Breakfast property type and 81% of people prefer private apartments.

<n> <b> 7. What do you infer from the clustering and forecasting trends of price by number of reviews graphs ?</b> </n>

From the clustering graph we can infer that the p-value for the variables review ratings, number of reviews, beds and sum of price is less than 0.05. This shows the selected variables have good correlation with each other. This is also very much evident in the upward trend of the forecasting visuals.

<n> <b> Inference </b> </n>

From the above analysis I could see the given categories of (price, room type, reviews, beds and host since) have a positive correlation.
This makes the analysis clear that there are lot of business opportunities expansion in the stable neighborhoods like Manhattan, Brooklyn and
Queens, followed by Bronx as well. There would be more price revenue generated for investors if they prefer investing on apartments and private houses.

<n> <b> Final Dashboard link </b> </n>

https://public.tableau.com/app/profile/parkavi.srinivasa/viz/Airbnb_DataVisualization_forecasting_visuals_dashboards_withSheets/AirBnB-NeighborhoodAnalysis?publish=yes

I have attached the final dashboard version with all the work sheets and the dataset that I had used for this analysis.

## Challenges 

Following were the challenges that I had faced throughout the development of this project:

1. Having null values in the date field made me to skip few of the records for plotting the visuals
2. There were couple of outliers in the data. There were few zipcodes that did not even belong to the neighborhood of given New York cities.
   For example: zipcode 07112, belong to the Newark region of the New Jersey state, but it was grouped under the New York cities and expecially
   for Manhattan.
3. Also, had to exclude many of the records during the plotting of visuals by quarters as there are not much of property-type entries available
   other than few major ones
4. I had difficulty in formulating the sequence of the analysis, as I started with exploring the neighborhoods by average price. But later I
   was able to arrive at meaningful sequential analysis and clear insights.

## Future Goals

If I had more time, I would have figured few other data sources to identify more key indicators such as check in and check out dates, which would have helped me identify, during which part of the year and the span duration the customers preferred to book the properties in the neighborhoods given.
