# Data115-Project

### Motivation
For my personal data set project I was interested in doing something with sneakers involved as I am into reselling and love sneakers. I decided I wanted to look at sneakers to see how time after the release of a sneaker affected sales, and how shoe size affected sales of certain sneakers. More specfically I looked at 3 yeezy V2 colorways, some were released at the end of 2016 and the other one was at the beginning of 2017 to see how yeezy sales were when they were trending more.

### Data Sources
For my data source I went to StockX which is an online marketplace for buying and selling sneakers and was able to find data of Yeezy and Off-White nike shoes from 9/1/2017 to 2/13/19 that they published for free. The data was orginalally used from StockX for a data analytics competetion they had for people to perform analysis on the data to win money. The data set had a total of 99,956 total sales including 27,794 Off-White sales and 72,162 Yeezy sales. These sales were also only for the United States.
 
 ### Data Process
 To process the data I didn't have to do much. I converted the Sale Price and the Retail Price to remove the dollar sign so I could work with numbers in my jupyter notebook. Other than that I just broke up the data in my analysis by column to work with indiviual columns of data such as 'Sale Price', and created new data frames for each yeezy. Also, I had to covert date times so I could that they were friendly to work with on jupyter notebook I did this via pd.to_datetime(df['column of data']).
 
 ### Visualization 
 For my first visualization I made a graph of Yeezy sales vs time after the release with  the given data I had as they released a little before all the data in file. I looked of 3 different Yeezys that were 'Core-Black-Red','Core-Black-Green','Cream-White' which all retail price was $220. I color coded each yeezy and made it into a scatter plot. In my scatterplot I seperated the graph to around 6 month increments to report average sales of those months for each yeezy. Also I reported a rate of change from month to month of sales.
 ![figure1data115](https://user-images.githubusercontent.com/63420549/101312535-daff7280-3808-11eb-9ad2-38760546a15f.png)
 
 For my second visualization I made graphs of each Yeezy in graph 1 and looked at which shoe sizes were being sold at at higher prices. To do this I made in shoe size vs sale price scatter plots of each Yeezy. I decided to make different graphs so the data points didn't look messy. 
 
 ![image2data115](https://user-images.githubusercontent.com/63420549/101312635-19952d00-3809-11eb-8537-8645a2183ee7.png)
 
 
