# Clustering the Countries by using Unsupervised Learning

*The dataset for this project originates from the [Unsupervised Learning on Country Data](https://www.kaggle.com/rohan0301/unsupervised-learning-on-country-data)*
<br>


### Objective:
To categorise the countries using socio-economic and health factors that determine the overall development of the country.

### Problem Statement:

- HELP International have been able to raise around $10 million. Now the CEO of HELP International NGO needs to decide how to use this money strategically and effectively. So, CEO has to make decision to choose the countries that are in the direst need of aid. 
- Our job is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then you need to suggest the countries which the CEO needs to focus on the most.


## Attribute Information

The data is contains values of different features are from different sources. The objective to suggest the countries which needs help of the money.

### Variables

1. **country :** Name of the country
2. **child_mort :** Death of children under 5 years of age per 1000 live births
3. **exports :** Exports of goods and services per capita. Given as percentage of the GDP per capita
4. **health :** Total health spending per capita. Given as percentage of GDP per capita
5. **imports :** Imports of goods and services per capita. Given as percentage of the GDP per capita
6. **Income :** Net income per person
7. **Inflation :** The measurement of the annual growth rate of the Total GDP
8. **life_expec :** The average number of years a new born child would live if the current mortality patterns are to remain the same
9. **total_fer :** The number of children that would be born to each woman if the current age-fertility rates remain the same
10. **gdpp :** The GDP per capita. Calculated as the Total GDP divided by the total population.


<hr>

## Dataset

| Number of Instances| Number of Attributes | 	Numeric Features	| Categorical Features	| Missing Values| 
 | :-------------: | :------------: | :-------------: | :------------: | :-------------:| 
 | 167	| 10| 9	| 1	| Null| 

<hr>


<hr>

## Clusters

![alt text](https://github.com/rahulbale/Data-Science-Machine-Learning-Project/blob/main/Donation%20Clustering%20for%20Countries/output/cluster.png)

<hr>

## Conclusion

**Countries which CEO should share out funds**

- **Cluster 1 :** This group of Countries lies in low for all the factors represented in the dataset features, CEO Should focus on this countries, as he must raise 70% of money. In Addition, CEO should encourage them to generate increase in health care system, high exports and moderate import which can increase income, lifestyle, gdpp and decrease child mort rate. 
- **Cluster 4 :** 25% should be distributed to this country, to encourage them increase in healthcare system and exports. 
- **Cluster 0 :** With small-scale healthcare system 1-5% should be alloted to this countries. 

**Countries which CEO should not share out funds** 
- **Cluster 2 :** This country should center of attention towards increase in exports and decrese in imports which will sharp there gdpp.
- **Cluster 3 :** There is similar discription as Cluster 2 Country, but this countries should focus more towards increase in gdpp.
