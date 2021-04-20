# Capstone_Project_rest 
## (Introduction/Business Problem)
A friend comes to me because he wants to open a Japanese restaurant in Seville, Spain. As I am from Seville, he thinks that I will be able to help him in the    decision due to my knowledge of the city.

Unfortunately, I have not lived there for a long time, and my knowledge of the restoration in the area is somewhat outdated.
In any case, I offer to help him using the data available on the internet and my "vague" knowledge of data science.
Between the two of us, I said, I am sure we will find the right place to establish it.

## (Data description)
The first thing is to know some information about the business we want to set up:
  1. Restaurant type: Japanese food / sushi
  2. Desired location: city center
  3. Size: small / medium

The data to be used will be the foursquare restaurant database and some statistical tools to find the best area to locate it based on its direct and indirect competitor.

## (Metodology)
  1. Ask the client (friend), 3 possible locations where he would like to install his restaurant
  2. Search through foursquare for the closest sushi restaurants within a radius of 1 km in the 3 areas.
  3. of the 3 closest restaurants evaluate current ratings to see which competitors there would be and how close they would be.
  4. based on the results and other data obtained by the client regarding the premises and their prices by area. Choose a location.

## (Results)
  Finally, the data has shown us the following information:

1. There are few competitors in the center of seville for our sushi restaurant.
2. within the 3 locations the results are as follows:

| LOCATION| PLAZA NUEVA| ALFALFA| ALAMEDA|
| ----- | ---- | ----- | ----- |
|nearest restaurant distance 1 | Sibuya Urban Sushi| Sushi Jamon Bar| Sushiteka|
|nearest restaurant distance 2 | Mc'Sushi | Sibuya Urban Sushi| Akira Sushi & Cocktail Bar|
|nearest restaurant distance 3 | Sushi Man | Mc'Sushi | De Fu Sushi|
|distance 1 (m)| 96| 164| 180|
|distance 2 (m)| 331 | 264| 220|
|distance 3 (m)| 355 | 455 | 268|

3. There are no ratings for any of the restaurants. Therefore, it will not be a relevant variable.
4. Most of the sushi restaurants in Seville are more than 500 m away from the alfalfa as you can see the following histogram.

https://github.com/fvelez-bracho/Capstone_Project_rest/blob/main/Unknown-32.png
