# **Elite Scientist - D.C. Residential Properties**
Nisrina Dinda D - Muhammad Dhiaz R

# **Table of Content**
- Introduction
- Problem Statement
- EDA
- Modeling
    - Clustering
    - PCA
    - Regression
- Conclusion  

# **Introduction**
Washington D.C is the Capitol City of USA. With a growing population of 700.000 , this has become one of the most expensive city in the world. Along with it's growth housing has become one of the biggest demand for the city. This Dataset provide us with Property prices along with census data of Washington D.C


This Data comes with 5 Datasets , which are

1. D.C Properties
2. Census Tract
3. Raw Address Point
4. Raw Condominiuum Data
5. Raw Residential Data


# **Problem Statement**
How could we utilize the data provided to better predict housing prices to avoid both overpricing and undedrpricing.


# **EDA**
Dataset used are D.C Properties and Census Tract as the other datas are already represented by those 2. Our Data Cleansing consist of removing outlier , handling missing values, and selecting feature.

Key Insight :
    1. No Features is strongly lineary correlated with our target, thus we can   deduce it is a non linear relationship

    2. There are consistant pattern in a location with house pricing and median income in the area

    3. Since both type of housing ( residential and condominium ) has vastly different character of data , it would be appropriate to build 2 models instead of 1

    4. Since the abondance , PCA will be conducted

    5. Clustering will also be conducted to better group our district

# **Modeling**

**Principal Component Analysis**
PCA is used to reduce our dimensions. Features with strong correlation will be reduced using PCA


**Clustering**
Using K-means Clustering to group our district in order to get better result for our regression model

**Regression**
Various Model are tested to build regression model for residential and condiminium price prediction


# **Conclusion**
After Data Cleansing Conducted , we would cluster our data into 4 cluster based on the demographic of the location.

Our cluster would become one of our variables. Two different models are constructed based on the type of residental source.


For Residential , the most optimal model is Random Forest and for Condominium , the most optimal model is also Random Forest