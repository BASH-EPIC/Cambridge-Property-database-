# Cambridge-Property-database-TABLEAU
# Assignment Summary

 This project is worked on the Cambridge Property database from Cambridgema.gov. The purpose of this project to build research questions according to data and create visualizations to display solutions of questions. We used statistical methods to define behaviors of properties of Cambridge, Massachusetts. Tableau has been used visualization tool for describe our works on dataset. By help of these visualizations and research, we can gain useful insights about sold properties in particular locations and which factors impact on properties and which patterns and trends happen in properties of Cambridge location. 
# Analysis
    First research question is about:
1.	What was sale price in 2019 according to estimation of year? We are interested to observe price of properties in Cambridge before Pandemic period starting.
![image](https://user-images.githubusercontent.com/81670865/177657121-11e43e15-4010-4833-a0b2-c1f8bd564418.png)
This graph shows Average Sale price for Year of Assessment from 2015 until 2022; sale price is available between 2016 and 2021 years. In this line graph, we can easily observe change of average sales price for 2019 is 1,190,550. It is interested that although pandemic period performance of almost all industry has decreased, the price of properties in Cambridge was continuing to increase during 2020 and 2021. We displayed trend line of Sale Price for Year of Assessment. By help of this trend line, we can define that average sale price of properties for year of assessment achieved trend line in 2020. Although that properties observed increase from 2016 to 2017 for sale price, this price is below of trend line.
P-value:	0.0003948
Equation:	Avg. Sale Price = 100341*Year Of Assessment + -2.0141e+08
Coefficients	
Term	Value	StdErr	t-value	p-value
Year Of Assessment	100341	9161.7	10.9522	0.0003948
intercept	-2.0141e+08	1.84929e+07	-10.8912	0.0004035
These statistical measurements belong to trend line. We can see that p-value is lower than confidence level (alpha=0.05, which commonly used), it means our prediction works significantly. 
2.	Define Average Sale Price according to Property class. 
![image](https://user-images.githubusercontent.com/81670865/177657165-a0a6c661-13d5-4b58-800e-c63c62d6defa.png)
This tree map shows average sale price for Private Education property, Vacant Property and Other class property. Color and size show us average sale price. We created 3 groups: which one contains only private education properties, second one contains only vacant property and third one shows rest of them as Other. We can see that Private Education property takes the largest place of properties within 775thousands average sale price. 
3.	Define average assessed value in terms of condition overall grade of Cambridge Properties. Sort average building value from the lowest to the highest according to condition overall grade.
![image](https://user-images.githubusercontent.com/81670865/177657191-10570541-1f98-4ff4-ad8a-4c1189daebfb.png)
In this graph provides us average assessed value which is about total assessed value according to overall grade of building in Cambridge.
We can see that when the overall condition of building increases from fair to special, average value of building increases as well as. At top right, we can see conditions clusters which indicates overall condition grade by different colors. Additionally, we can easily see exact average assessed value for each condition. At the bottom, we can see grand total which contains all condition grade, by help of it, we can all condition grade’s average assessed value is almost 600M.
4.	Make comparisons of average property tax amount and average sale price for 10 years between 2019 and 2020.
![image](https://user-images.githubusercontent.com/81670865/177657217-72f2e7af-16e7-4323-b387-5a1cf21a7a0b.png)
Green bar charts shows us Average tax amount for year of particular sale date, and orange line shows average sale price for paricular sale year. We have indicated the highest tax amount for 2016, in which average sale price showed increase in spite of the highest tax amount. The lowest tax amount is observed for 2020 within 7459$, in which average sale price is in the highest level within above 60M.
5.	Define top 5 exterior style and their distribution among properties.
![image](https://user-images.githubusercontent.com/81670865/177657250-561d3008-79ec-49e6-b1f8-48c09fbc88c2.png)
We can see count of exterios style at left side and name of top exterior style at top right side. Colored bar charts shows 5 top exterior styles: Apartment which is the highest one within 27060, Conventional as second style, Flat, Old style two fam as third used style, and Victorian as the lowest exterior style among top 5 styles within 4965, which is lower than 60% of average level. Second lowest exterior style among 5 style is Flat which reached 60% of average level. Rest of them achieved 80% of average level. 
6.	Create Map of Average assessed value of properties in and around Boston.
 ![image](https://user-images.githubusercontent.com/81670865/177657267-605e7def-7869-4fcf-9d7c-f3bb456ae420.png)
We created map which based on generated Longtitude and Latitude shows us Average assessed value in and around Boston according to Owner State. By help of legend we can see selected owner state color which shows colored cycles on map. We defined Chestnet Hill as the most expensive location within 3,574,561 (3M). The cheapest location is assigned in Roslindale within 604,945. Map background is selected as outdoors. 




