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

> The two targets have been explicitly created.
* 'type' column contains binary values 0 and 1 denoting red wine and white wine, respectively.
* 'quality_label' contains object values denoting the quality of the wine as:
  * low if quality is less than or equal to 5
  * medium if quality is between 6 and 7
  * high if quality is greater than 7
  
**Instructions to follow while going through the notebooks:**
1. Download the latest version of python. [Click here to download Python!](https://www.python.org/downloads/)
2. Download Anaconda [Click here!](https://www.anaconda.com/distribution/)
> Libraries included in Anaconda
- - - -
![Libraries included in Anaconda](https://www.anaconda.com/wp-content/uploads/2018/11/distro-01-1.png)
> **NOTE:** If you already have the above installed, you're good to go!
3. Download the .ipynb files on your system
4. Since I have written the code on Google Colab, you can upload it and execute it on Google Colab in the following order:
    * The 'Wine_Dataset_(Visualization).ipynb' notebook has the different visualizations to understand the data.
    * The 'Wine_Type_(Logistic_Regression_2_Features).ipynb' notebook has the raw code as well as sklearn's Logistic Regression model to predict the type of wine.
    * The 'Wine_Quality_(Neural_Networks).ipynb' notebook has the raw code to implement neural networks for predicting the quality label of the wine.
> **NOTE:** In the first notebook, I am saving the combined dataset (red wine and white wine) on my drive. To do that, you need to mount your drive onto colab and after the authentication has been completed, you can make a copy of it on your drive and reuse it in other notebooks. For reusing it, you need authentication again. The code as well as documentation for that has been explicitly mentioned in the notebook.
