# Wine-Dataset
Capstone - 1 (MLFA)

**Introduction**
Wine is an alcoholic beverage made from fermented grapes. It will be very interesting to analyse the chemical attributes of wine and understand their relationship with the types of wine and also the quality of it.

In this project, there will be two predictions:
* Predicting the type of wine as red or white
* Predicting the quality of wine as low, medium or high

**About the dataset**

This dataset contains about 6497 instances (samples) and 12 columns (attributes), 1599 being red wine and 4898 being white wine.
The different attributes are floating values which are based on chemical tests on the samples.

*Attributes*:
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
12. quality

*Targets*:
> The two targets have been explicitly created.
* 'type' column contains binary values 0 and 1 denoting red wine and white wine, respectively.
* 'quality_label' contains object values denoting the quality of the wine as:
  * low if quality is less than or equal to 5
  * medium if quality is between 6 and 7
  * high if quality is greater than 7
