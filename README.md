# Diamons-price-analysis

The goal of this project is the prediction of the price of diamonds based on their characteristics (weight, color, quality of cut, etc.). 
## INPUT folder
- diamons_train.csv: data provided to train the different machine learning models.
- dismons_test.csv: data provided to test the created models. 

### Features
  -id: only for test & sample submission files, id for prediction sample identification.
  
  -price: price in USD
  
  -carat: weight of the diamond
  
  -cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
  
  -color: diamond colour, from J (worst) to D (best)
  
  -clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
  
  -x: length in mm
  
  -y: width in mm
  
  -z: depth in mm
  
  -depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
  
  -table: width of top of diamond relative to widest point (43--95)
  
  ## SRC 
  -clean_data: provides a function to clean both (test and train) dataframes
  ## Diamons.ipynb
  Jupyter notebook with all the code used to train and test different models.
  libraries used: sklearn and h2o

  ## OUTPUT
  -final csv with the predicted price
