# U.S. Flight Delay Dashboard

## Introduction and Data

Air travels have a significant role in the economy of agencies and airports. One of the important modern life challenges of airports and airline agencies is flight delay. A flight delay is when an airline flight takes off and/or lands later than its scheduled time. The Federal Aviation Administration (FAA) considers a flight to be delayed when it is 15 minutes later than its scheduled time. Flight delay is inevitable and it plays an important role in both profits and loss of the airlines.

I used HTML5, CSS6, Javascript, and D3 to create this dashboard, the goal is to take a look inside into the U.S flight delay data by using many various visualizations such as chart, donut, force, choropleth map to answer these questions: how does the total number of flight delay change, which airport has the most flight delay, the relationship between origin and destination airports.

The data is collected from the Bureau of Transportation Statistics, Govt. of the USA. This data is open-sourced under U.S. Govt. Works. This dataset contains all the flights in the month of January 2019 and January 2020. There are around 400,000 rows in this file and 21 feature columns indicating the features of the flight including information about origin airport, destination airport, airplane information, departure time, and arrival time. The data used to create this dashboard is sourced from U.S Flight Delay Dataset

There are 21 columns in the dataset, but I only used columns which are listed below:

|    Column name    |                                   Description               |
|-------------------|-------------------------------------------------------------|
|OP_CARRIER         |Code assigned by IATA and commonly used to identify a carrier|
|ORIGIN             |Origin Airport                                               |
|DEST               |Destination Airport                                          |
|DEP_DEL15          |Departure Delay Indicator, 15 Minutes or More (1=Yes, 0=No)  |

## Flight Delay Visualization

Figure 1: Bar chart and Donut chart showing Flight Delay, Total Flight, and Flight Delay within the Airlines

Figure 2: Force Layout Graph showing the flight delay from the origin and the destination between the top 20 airports

Figure 3: Choropleth map showing the flight delay in the U.S. States

## Conclusion

The bar chart illustrates the total flight delay and the total flight in the U.S. in January 2019 and 2020. Overall, it is clear that the figures for total flights had an increase from 583,985 to 607,346 between the periods. However, the number of flight delay fell over the period from 105,222 in January 2019 to 82,285 in January 2020.

The donut chart compares the flight delay within the airlines. In January 2020, American Airlines (AA) had the most flight delay with 11,348 flights, Skywest Airlines (OO) kept the second with 10,692 flights. The third airline that had more flight delay belongs to Southwest Airlines (WN) with 10,321 flight delay.

The force layout graph shows the network visualization between the top 20 airports. We can see that all airports had a connection with the others.

The choropleth map represents statistical flight delay data through various shading patterns on each state in the US. In this case, Texas, California, Arizona, Florida,... show the flight delay higher than other states.

## Reference

US Flight Data for the month of Jan 2019 and Jan 2020: [U.S Flight Delay Dataset](https://www.kaggle.com/divyansh22/february-flight-delay-prediction#Feb_2020_ontime.csv)
