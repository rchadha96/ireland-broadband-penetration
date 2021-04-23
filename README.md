# Domestic Broadband Penetration
Project Goal: To demonstrate the penetration of Domestic Broadband Networking in Ireland using R

## Introduction
To study the penetration of broadband networking in Ireland by investigating and analysing the percentage of Ireland’s population that are broadband subscribers at county and electoral division levels with the help of thematic maps. This analysis is used to find out the parts of the country that have higher and lower penetration rates and to observe the trends in the distribution of broadband across the country.

This project is done as a part of coursework for NCG608[A]-Introduction to Geographical Information Science.

### Percentage of Broadband users across Counties
#### Mode: Natural Breaks (Jenks)

![](/images/sk1.PNG)

#### Mode: Equal Count (Quantile)

![](/images/sk2.PNG)


#### Mode: Equal Interval

![](/images/sk3.PNG)

## Discussion

The three maps with different modes at County and Electoral Division level highlight that Ireland has extreme areas, which are well-developed and urban and the others the ones which are rural and not well equipped. It is apparent that Dublin and its nearby counties have the highest percentage of broadband users and this broadband users decreases towards North, which might indicate that either they have low population or they don’t use broadband. Similar trend is seen at ED Level.
Maps have been produced to represent broadband users only and does not include users with OTH, NS and N as specified in TABLE 3. 

Class Intervals:
•	Equal Intervals: each class has the same size, values from 58 to 86 with 5 classes and each class size of 5.6.

•	Quantile: each class will have the same number of elements inside (the idea of a boxplot).

•	Natural Breaks (Jenks): the variance within each class is minimal while the variance between classes is maximal.

In the case of Ireland, based on past progress and current plans, it is unlikely that the 30 Mbps will be available to all citizens by 2020.

## Conclusion 

•	The highest number of broadband and internet is the Dublin area which supports the fact that there exists large number of personal computers, industries and population density.

•	Households in sparsely populated and lagging regions also have significantly lower rates of penetration which are difficult to serve from the perspective of a profit driven provider.

•	I found Natural Breaks (Jenks) the best way to split up the range as it minimizes the variation within each colour.

### References
•	QGIS Tutorial: http://www.qgistutorials.com/en/

•	NCG608[A] module presentations and notes.
