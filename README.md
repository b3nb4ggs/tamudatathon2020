# TAMU_Datathon2020

**Challenge:** City Search Tool <br />
**Problem:** Find a way to select the best place on earth to move to based on (suggested) median income of a location, cuisine, primary ethnicity, pollution index, happiness index, number of coffee shops or microbreweries in the city, etc. <br /> <br />


***Columns***  <br />
City Name: City Name <br />
Country: Country Name <br />
Purchase Power: comparing average cost of living with the average local wage <br />
Pollution: low is good. A score of how polluted people find the city, includes air, water, and noise pollution <br />
Health Care: compiled from how citizens feel about their access to healthcare, and its quality (average of health care column from numbeo and movehub dataset) <br />
Quality of Life: balace of health care, pollution, purcahse power, crime rate to give an overall quality of life score <br />
Cost of Living: is an estimation of consumer goods prices including rent comparing to New York City <br />
Safety Index:high safety index means the city is considered very safe <br />
Crime Rating: lower the score the safer people feel in the city <br />
Climate Index: is an estimation of the climate likability of a given city or a country. It is in the range [-100, +100] (higher is better) <br />
Traffic Time Index: average oneway time needed to transport in minutes <br />
lat: latitude of city <br />
lng: longitude of city <br />
City_Codes: City Name encoded as integers  <br /> <br />

### Data Use: 
<p>Effectively used data, acquired additional data </p>

```diff
+ aquired new data by importing three datasets we found

```


### Analytics: 
<p>Effective application of analytics (bonus points for ML/clustering techniques)</p>

```diff
+ Used a decistion tree and random forest regressor

```

 ### Visualization: <p>Solution is visually appealing and useful (Bonus points if you create an interactive tool/application/website)</p>

```diff
+  Used interactive widgets to show our graphs and to let user choose what features to use in the model

```

### Impact: 
<p> Clear impact of solution to solving problem</p>

```diff
+  Solution is to get through the modeling section and get the list of cities, then look up the city based on it's code. <b>The impact of our project is that people will be able to select the best place on earth to move to, based on the features and importance values they they hold to themselves.</b>

```

**Resources** <br />
One data set is from TAMU Datathon from City Search Tool page in TD website and retrieved from https://www.datalogz.io/ <br />
We got three datasets from https://www.numbeo.com <br />
Specifically our Multi_Value_Numbeo.csv is from https://www.numbeo.com/cost-of-living/rankings_current.jsp <br />
The Quality_of_Life_Numbeo.csv is from https://www.numbeo.com/quality-of-life/rankings_current.jsp <br />
The Property_Prices_Numbeo.csv is from https://www.numbeo.com/property-investment/rankings_current.jsp <br />


