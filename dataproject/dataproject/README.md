# Dataproject 

This dataproject presents data on total danish import from 1997 to 2019. The import is divided into nine different categories which are the following: 
   
  Live Animals, Food, Beverages and Tobacco 
  
  Crude Materials, Inedible, except Fuels
  
  Chemicals and Related Products 
  
  Manufactured Goods Classified Chiefly by Material
  
  Machinery (excl. transport equipment)
  
  Transport Equipment
  
  Miscellaneous Manufactured Articles 
  
  Mineral Fuels, Lubricants and Related Materials 
  
  Vessels, Aircraft etc.   
  
The data of interest is downloaded from Statistics Denmark (Danmarks Statistik: https://www.statistikbanken.dk/UHV1) and originally named "UHV1". The dataset consists of seasonally and non seasonally adjusted numbers but this analysis only examine the non seasonally adjusted numbers. The danish import data is in nominal prices which we want to change into real prices. Hence we import a second dataset from Statistics Denmark called "PRIS112", which contains the danish consumer price index (CPI). We will use the CPI data to transform the nominal prices into real prices by merging the two datsets together and dividing the consumer price index on the entire dataset. 

In order to examine the evolution of the import data we choose the calculate the percentage change growth rate, which gives us a new datset. To get an overview of which categories that have experienced the highest and lowest growth rates over the years we do a basic statistic analysis. Finally we illustrate the evolution of the data in an interactive plot, where we are able to adjust the category of interest as well as the time period. 

Note: To be able to repreduce our results the user should run the entire code from top to bottom. Moreover some of the code does not respond well to being run severeal times, why the user should re-run the entire code if the code produce wrong results. 

The **results** of the dataproject can be seen from running [Dataproejct_2020.ipynb](Dataproejct_2020.ipynb).

**Dependencies:** Apart from a standard Anaconda Python 3 installation, the project requires no further packages.
