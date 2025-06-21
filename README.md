# World Happiness Index :slightly_smiling_face:

**"Dont worry, be happy" & "Hakuna Matata"**  

Easier said than done! 2020 has been a mess for us all. With all the negativity around us, somtimes the simple mantra of "just be happy" seems unachievable.
So we asked ourselves: "What makes people happy?"

To find an answer to that questions, we put all data visualization tools we own in our suitcase and embarked on a journey to figured out the answer to exactly this question. Our journeys took us from Switzerland to the USA, to Germany and to Colombia.
From each destination, we brought back one saying, proverb or phrase about happiness, and explored whether they can help us answer the question which has puzzeld humanity for so long.

Presentation file above (Word Happiness Index.pptx).

**“Money can’t buy you happiness”** :money_with_wings:   
*Swiss philosopher Jean-Jacques Rousseau*  

First, we explore “Money can’t buy you happiness”. To investigate the claim, we seek to explore the relationship between economic indicators and happiness. To proxy a measure of happiness, we retreived a dataset from Kaggle that includes data on countries measured in an index called the happiness score. We then pick 4 variables of interest that best represents a society’s economic wellbeing (GDP per capita PPP, Gini coefficient, GNI per capita & Employment Rate) from the Gapminder dataset. We hypothesise that higher income and more equal societies with ample jobs are happier. Our analysis interestingly finds that more money is correlated with higher level of happiness in all countries.

**“Happy stomach, happy heart”** :hamburger:  
*Colombian saying*   

Secondly, we explore “Happy stomach, happy heart”. In order to explore how food impacts happiness, we are using the measure of kcal per capita per person per day from the Food and Agriculture Organization of the UN. Additionally, we are interested in seeing if countries who have more food tend to score higher on the happiness index as well as if certain types of food impact happiness more than others. We find that six out of the top 10 fish consuming countries are also above average in terms of happiness score. Furthermore, Iceland, Denmark, and Norway are all in the top 10 in happiness overall. However, we still cannot conclude a causal relationship.

**“True happiness is when you are free of appointments and tipsy”** :clinking_glasses:   
*German saying*   

Next, we explore the saying “True happiness is when you are free of appointments and tipsy”, using data from FiveThirtyEight.  Here we want to explore how happiness and alcohol consumption are related, while at the same time taking into account the relationship between happiness and GDP per capita as it could be that richer countries buy more alcohol. Also, we explore which type of alcoholic beverage is the most consumed in each country and which group has the highest happiness score based on their most consumed beverage.

**“Happy wife, happy life”** :couple:  
*American saying*   

Finally, we explore “Happy wife, happy life” by looking at the relationship between gender equality and happiness, using data from the World Bank. Based on our results, gender equality is a significant factor when considering level of happiness in a country. Countries, with a considerably smaller population size and located in Europe, tend to have a high index of gender equality and happiness.

**Prediction Model** :dart:  

Last but not least, we build a prediction tree model to see how well our four sayings predict how happy a country is. In doing so we focus on the following variables that describe our sayings:

1) Wealth: Gini-index and GDP per capita (in k)
2) Food: Food supply in kcal per capita per day
3) Alcohol: Litres of pure alcohol consumed per capita
4) Gender Equality: Gender equlaity index

We are plotting our predictions made on the testing data set against their actual values to observe out-of-sample performance. While our model does predict rough tendencies, many countries diverge from the best-fit line. However, for our example of Great Britain, our prediction seems to be very accurate, although we note that our prediction model should be taken with a grain of salt.


**Data sources:**  
1. World Happiness Report: https://www.kaggle.com/unsdsn/world-happiness
2. Gapminder: https://www.gapminder.org/
3. Food and Agriculture Organization of the United Nations: http://www.fao.org/faostat/en/#data/FBS
4. World Bank: https://tcdata360.worldbank.org/indicators/h4d0104f0?country=BRA&indicator=41933&viz=line_chart&years=1975,2018
https://data.worldbank.org/indicator/NY.GDP.PCAP.PP.CD
5. FiveThirtyEight: https://fivethirtyeight.com/features/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/
6. IMF World Economic Outlook: 
https://knoema.com/IMFWEO2020Oct/imf-world-economic-outlook-weo-database-october-2020





